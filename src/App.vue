<template>
  <div id="app">
    <Header/>
    <About/>
    <Sobre/>
    <Skills/>
    <Footer/>
  </div>
</template>

<script>

import Header from './components/Header.vue'

import About from  './components/About.vue'
import Sobre from './components/Sobre.vue'
import Skills from './components/Skills.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
   Header,
   About,
   Sobre,
   Skills,
   Footer
  }
}
</script>

<style scoped>
  
</style>
