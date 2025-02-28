---
layout: posts
permalink: /About/
author_profile: true
title: '<p class="title-post" > About Me </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner4.jpg
excerpt: '<p class="excerpt-post"> Background, hobbies, values and CV</p>' 
---

<h1> From the moutain… </h1>

<p align="justify">
I was born in the French Alps (Haute-Savoie), but I didn’t have the chance to enjoy the diversity of alpine habitats during childhood. One event, however, put me on the track to become a biologist: the emergence of a bright red showy tulip flower that I planted with my grandmother. How can an onion give such a beautiful flower?
As an adult, I started hiking with my brother and exploring the Alps. In these long walks, I became aware of what surrounded me. The exceptional diversity and complexity of ecosystems lead me to engage in a B.Sc. in Biology at Université de Lyon. 

<h1> …To the academy </h1>

<p align="justify">
From a difficult socio-economic context, I was the first of my family to make it to university. Full of curiosity and determination, I decided to move to Canada in a student exchange program in my last year of my bachelor's degree. 
This gave me the opportunity to be an intern in Simon Joly’s lab, working on collecting preliminary data to assess if urbanization had an impact on flower shape in Impatiens capensis. I immediately liked doing research and decided to pursue my academic journey to, one day, become a professor. 
Back in France, I enrolled in a M.Sc. in plant biology. Because Canada missed me, I decided to return to Montreal for my internships, one in the lab of Daniel Kierzkowski, studying growth patterns of floral organs in Arabidopsis thaliana, and next in the lab of Simon Joly to develop a protocol of 3D flower reconstruction by photogrammetry.
I then decided to enroll in a PhD program, to study flower evolution in an urbanization context.
 
</p>

<!-- <img-div>
<img width="600px" src="../assets/images/About5.jpg" class="center" />
<figcaption>Some field work during my PhD</figcaption>
</img-div>


<p align="justify">
Under construction. 
</p>

<img-div>
<img style="Padding: 10px 10px 10px 10px; float:left;" width="525px" src="../assets/images/About1.jpg"/>
<img style="Padding: 10px 10px 10px 10px;" width="525px" src="../assets/images/About2.jpg"/>
<img style="Padding: 10px 10px 10px 10px;float:left;" width="525px" src="../assets/images/About3.jpg"/>
<img style="Padding: 10px 10px 10px 10px;" width="525px" src="../assets/images/About6.jpg"/>
<figcaption>And some places where we went for fish samplings during my PhD</figcaption>
</img-div> -->


<!-- Back to top button -->
<button type="button" class="btn btn-danger btn-floating btn-lg" id="btn-back-to-top">
  <i class="fas fa-arrow-up"></i>
</button>

<script>
//Get the button
let mybutton = document.getElementById("btn-back-to-top");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function () {
  scrollFunction();
};

function scrollFunction() {
  if (
    document.body.scrollTop > 20 ||
    document.documentElement.scrollTop > 20
  ) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}
// When the user clicks on the button, scroll to the top of the document
mybutton.addEventListener("click", backToTop);

function backToTop() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>