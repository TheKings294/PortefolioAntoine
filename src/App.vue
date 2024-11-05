<script setup>
import NavBar from './components/NavBar.vue';
import Foot from './components/Foot.vue';
import textHome from './components/icons/textHome.vue';
</script>

<template>
  <header id="Header">
    <NavBar></NavBar>
  </header>
  <main>
    <textHome id="Name"></textHome>
  </main>
  <footer>
    <Foot></Foot>
  </footer>
</template>

<style scoped>
</style>
