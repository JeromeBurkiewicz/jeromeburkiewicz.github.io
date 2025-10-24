---
layout: posts
permalink: /research/
author_profile: true
title: '<p class="title-post" > Research </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner5_light.jpg
excerpt: '<p class="excerpt-post"> Urban Evolutionary Ecology, Flower Morphology and Pollination </p>' 
---


<h1> PhD Research </h1>

<p align="justify"> 
More than half of all human beings live in urban environments. Although cities occupy only 0.5% of the Earth's surface, they have a major impact on ecosystems and biodiversity through the destruction and fragmentation of habitats, pollution and increases in average temperatures (heat islands). By affecting biodiversity, cities also alter the interactions between living organisms. Flowers, for example, attract animals such as insects (bees, bumblebees, wasps, etc.) and birds (hummingbirds) to pollinate them so that they can reproduce. Over time, flowers have even developed special shapes and sizes so that when an animal visits a flower, it touches the stamens and carries more pollen to the pistil, ensuring efficient reproduction. However, urbanization is changing the abundance and diversity of pollinators. As a result of these changes, the shape and size of flowers can be expected to evolve to better suit local pollinators, enabling plants to reproduce more efficiently (natural selection). Yet, there are very few studies that investigated the impact of urbanization on flowers and their pollinators in urban environments.
<p align="justify"> 
My PhD focuses on three aspects of the spotted jewelweed flower evolution in an urbanization context: first, I compared urban and natural populations in the Quebec, Montreal, Ottawa, and Toronto regions, looking for flower morphology evolution in controlled and fieldwork conditions. Second, I studied natural selection on flower morphology in urban and natural contexts. Third, I collected material to find genetic loci associated with urbanization and conduct a GWAS to detect specific loci involved in the adaptation of flower morphology to urbanization.
<p align="justify"> 
Urbanization is drastically changing the environment in which organisms live. However, it also gives us a better understanding of its effects on the evolution of flowers. Understanding this phenomenon is essential: it paves the way for urban development solutions that make ecosystems more robust and resilient in the face of human pressures while guaranteeing the survival of ecosystem services that are essential to humans, such as pollination.

</p>

<img-div>
<img style="Padding: 10px 10px 10px 10px; float:left;" width="500px" src="../assets/images/fieldwork.jpg" />
<img style="Padding: 10px 10px 10px 10px;" width="468px" src="../assets/images/common_garden.jpg" />
<figcaption style="text-align: center">Photographing flowers in a natural site near Montreal, and lost in my common garden experiment</figcaption>
</img-div>


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