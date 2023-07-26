<template>
  <div id="app">
    <Navbar />
    <Section />
    <Carousel />
    <!-- Aquí puedes usar el componente Card -->
    <Card />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Section from './components/Section.vue'
import Carousel from './components/Carousel.vue'
import Card from './components/Card.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Section,
    Carousel,
    Card,
    Footer
  }
}
</script>

<style>
/* Estilos globales aquí */
</style>