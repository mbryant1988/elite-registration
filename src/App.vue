<template>
  <Navbar />
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/AppNavbar.vue';
import { event } from 'vue-gtag';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar
  },

  setup() {
    const pageView = () => {
      event('pageView', { method: 'Web' })
    }
    
    return {
      pageView,
    }
  },

  mounted() {
    document.title = "Register";
  }
}
</script>

<style>

html, body {
  margin: 0;
  padding: 0;
}  
@import "@/assets/colors.css";
#app {
 
  color: #2c3e50;
  background-color: var(--color-tertiary);
  width: auto;
}
</style>
