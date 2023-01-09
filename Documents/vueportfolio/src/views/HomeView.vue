<template>
  <head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
  </head>


<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="https://i.postimg.cc/0j6Ss9NY/mr-robot.jpg" style="width:100%">


  <a href="HomeView.vue" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="AboutView.vue" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="TestimonialsView.vue" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa-solid fa-comments w3-xxlarge"></i>
    <p>TESTIMONIALS</p>
  </a>
  <a href="ProjectsView.vue" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa-solid fa-briefcase w3-xxlarge"></i>
    <p>PROJECTS</p>
  </a>
  <a href="PhotosView.vue" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa-solid fa-image w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>
  <a href="ContactView.vue" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>


</template>


