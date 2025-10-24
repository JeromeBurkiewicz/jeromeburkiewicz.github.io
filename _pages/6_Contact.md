---
layout: posts
permalink: /contact/
author_profile: true
title: '<p class="title-post" > Contact </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner7.jpg
excerpt: '<p class="excerpt-post"> Email, social medias and research networking</p>' 
---

<h1>How to contact me</h1>

You can reach out to me or follow my work with these social media and websites. However, the quickest and most certain way to contact me remains my email: jerome.burkiewicz [at] umontreal.ca

<div class="center_contact">

 
   <a href="https://bsky.app/profile/jeromeburkiewicz.bsky.social">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="100px" src="../assets/images/bsky.png" />
   </a>

  <a href="https://orcid.org/0000-0001-6968-3506">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="100px" src="../assets/images/orcid.png" />
   </a>

   <a href="https://scholar.google.com/citations?user=hAuV0dAAAAAJ&hl=fr">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="100px" src="../assets/images/scholar.png" />
   </a>

</div>

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