<script setup>
import {RouterView} from 'vue-router';
import FooterSite from "./components/FooterSite.vue";
import NavBar from './components/NavBar.vue'</script>

<template>
  <NavBar/>
  
  <RouterView/>

  <FooterSite/>
</template>

<style scoped>
</style>
