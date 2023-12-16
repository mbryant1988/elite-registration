<template>
  <Navbar />
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/AppNavbar.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar
  }
}
</script>

<style>
@import "@/assets/colors.css";
#app {
 
  color: #2c3e50;
  background-color: var(--color-tertiary);
  width: auto;
}
</style>
