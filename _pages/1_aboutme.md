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

<h1> A little background </h1>

<p align="justify">
Under construction. 
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