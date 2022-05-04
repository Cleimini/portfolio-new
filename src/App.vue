<template>
  <Header />
  <Menu />
  <Hero />
  <Projects />
  <Skills />
  <Experiences />
  <Footer />
</template>

<script>
  import Header from './components/Header.vue'
  import Menu from './components/Menu.vue'
  import Hero from './components/Hero.vue'
  import Projects from './components/Projects.vue'
  import Skills from './components/Skills.vue'
  import Experiences from './components/Experiences.vue'
  import Footer from './components/Footer.vue'

  export default {
    components: {
      Header,
      Menu,
      Hero,
      Projects,
      Skills,
      Experiences,
      Footer
    },

    data() {
      return {
        
      }
    }
  }
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    margin: 0 auto;
    padding: 0 auto;
  }

  body, html {
    font: {
      family: 'Montserrat', sans-serif;
      size: 0.875rem;
    }

    scroll-behavior: smooth;
  }
</style>