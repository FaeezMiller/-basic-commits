<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: black;
}

    body,
    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
      font-family: "Montserrat", "sans-serif"
    }

    .w3-row-padding img {
      margin-bottom: 12px
    }

    /* Set the width of the sidebar to 120px */
    .w3-sidebar {
      width: 120px;
      background: #222;
    }

    /* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
    #main {
      margin-left: 120px
    }

    /* Remove margins from "page content" on small screens */
    @media only screen and (max-width: 600px) {
      #main {
        margin-left: 0
      }
    }
  
    *,
*::after,
*::before{
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;}

   h1{
  cursor: pointer;
  font-size: 20vw;
  color: transparent;
  background:url(https://i.postimg.cc/zXdg1nHp/textbg.jpg);
  background-size: 40%;
  background-position: 50% 50%;
  -webkit-background-clip: text;
}
.picture2{
  height: 90%;
  width: 95%;
}
.picture3{
  height: 90%;
  width: 95%;
}
.nasa{
  height: 200px ;
}
#home h1 {
  text-align: center;
  animation: 2s title infinite;
}
@keyframes title {
  0% {
      opacity: 0;
      transform: rotateX(90def);
  }
  50% {
      opacity: 1;
      transform: rotateX(720deg);
  }
  100% {
      opacity: 1;
      transform: rotateX(720deg);
  }
}




</style>
