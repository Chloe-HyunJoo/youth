<template>
  <div>
    <!-- <header>
     <a class="menuLink" href="#"><img class='main-logo' src= '../images/logo.gif'></a>
    </header> -->
    <router-view/>
  </div>
</template>

<script>
// import HeaderComponent from './components/main/HeaderComponent.vue'
// import footer from './pages/main/Footer.vue'
import main from './pages/main/main.vue'

export default {
  // extends: HeaderComponent, footer
  extends: main
}
</script>

<style scoped src = "../style.css"></style> 
<!-- This will import the css scoped to this componen only-->
<style lang="css">
   /*@import "~bulma/css/bulma.css";*/
   /* @import "~style.css"  this wii import the css globaally */
 </style>
