---
layout: posts
permalink: /blog/
author_profile: true
title: '<p class="title-post" > Blog </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner7.jpg
excerpt: '<p class="excerpt-post"> Concise summary of research papers in my field </p>' 
---


<h1> Blog </h1>

<p align="justify"> Under Construction.
</p>

<!-- <img-div>
<img style="Padding: 10px 10px 10px 10px;" width="800px" src="../assets/images/Paper1.png" class="center" />
<figcaption style="text-align: center">Figure A. <i>Chrosomus eos x eos-neogaeus</i> reproductive pathways, and main results of my first chapter.</figcaption>
</img-div>


<img-div>
<img style="Padding: 10px 10px 10px 10px;" width="800px" src="../assets/images/ME.jpg" class="center" />
<figcaption style="text-align: center">Figure B. The origin of the <i>Chrosomus eos x eos-neogaeus</i> reproductive pathways, and main results of my second chapter.</figcaption>
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