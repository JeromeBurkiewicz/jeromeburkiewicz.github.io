** Pour lancer la visualisation du site:
https://jekyllrb.com/docs/installation/ 

Installer Ruby (3.1.2);
Installer Github desktop;
Installer GitBash. 

## Noter que l'installation peut être un peu chiante - c'est la pire partie du truc :(

1. Open Git Bash in the website folder (right click, "open git bash here")
2. Écrire dans la terminal : bundle exec jekyll serve
3. Ouvrir le serveur sur un navigateur : http://127.0.0.1:4000


1. Pour changer les information sur la page d'accueil (landing page ou index):
	1.1 À la racine, il y a  le fichier "index.html". À ouvrir avec un gestionnaire de code (visual studio code ou autre). 
	1.2 Ce fichier permettra de changer la page d'accueil
2. Le dossier "_data" contient un fichier "navigation", où indiquer le nom des onglets du site web et quel fichier ils doivent ouvrir (e.g. l'onglet Outreach ouvre le fichier Outreach.md)
3. Le dossier "_pages" contient les fichiers markdown (md) à modifier pour changer les différents onglets du site web. On y change le contenu (e.g. le texte) mais pas la forme (e.g. le design/couleur).
4. Le dossier "_sass" contient les modifications css pour changer l'apparence du site web, mais seul les skins peuvent être modifiés! Voir la section 6.
	4.1 Les "skins" sont des ensembles proposés de couleur pour le site web (perso j'ai fait un custom)
		4.1.1 Pour changer de skin, voir la section 7
5. Le dossier "_site" ne doit pas être modifié! Ce dossier contient la "compilation" des éléments donnés dans les autres dossiers; il est donc override en permanence par Jekyll. 
6. Le dossier "asset" contient tous les objects à insérer dans le site web (pdf, photos) ainsi que le fichier main.css
	6.1 Il est possible d'ajouter des dossiers ici, il faudrat juste s'y référer dans le code des pages pour indiquer où est le fichier voulu
	6.2 Le fichier main.css (dossier css) contient TOUT le css. C'est pour moi plus simple de travailler comme ça, mais il overide les fichiers du dossier "_sass". 
7. À la racine, il y a le fichier "_config.yml". Ce dernier est important pour la configuration générale du site. 
	7.1 On retrouve dans ce fichier, au début, le nom du skin à utiliser
	7.2 à la section "site author", il est possible de changer la bio qui apparait sur le côté dans les onglets.
8. Le dossier "_layout" contient les information sur le position des objets sur une page. 
	8.1 En général, on utilise le layout "post" mais d'autres peuvent être utilisés.
	8.2 Perso, je ne touche que rarement à ces fichiers, je préfrère utilise des classes d'objets différents (et spécifier pour chaque classe comment l'objet doit se comporter)

** Les autres dossiers non mentionnés ne devraient pas être d'intérêts. 
** Ne pas changer les noms de dossiers, Jekyll les reconnaît automatiquement et changer les noms fera ensorte qu'il ne trouvera plus les infos.


Some comments: 

Walkthrough

VERY IMPORTANT : USE THE INSPECT FUNCTION TO CHANGE THINGS DIRECTLY IN THE BROWSER AND IF THAT'S OK, PUT THESE CHANGES IN THE SCRIPT AFTERWARD --- WAY QUICKER 
AND EASIER TO FIND THE CORRECT CSS ARGUMENT TO MANY THINGS


1. To change the highlighting, search in main.css for : ::selection {
    color: #333333;
    background: #FFBE8C
}

2. To change the footer : 
	2.1 Multiples places to go. First, _includes then footer.html to change content (link)

3. To change the lateral left text css, search for sidebar in the main.css

4. Change page title size : main. css: .page__subtitle
