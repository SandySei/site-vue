<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Backtotop from './components/Backtotop.vue';

</script>

<template>
  
  <div class="wrapper">
      
    <Header/>

    <main>
      <RouterView />
      <Backtotop />
    </main>


  
    <Footer/>

  </div>

</template>

<style scoped>

main {
 padding-top: 6vh;
 background-color: rgb(255, 255, 255);
}

</style>
