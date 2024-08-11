<script>
import Navbar from './components/Navbar.vue'
import Jumbotron from './components/Jumbotoron.vue'
import CTA from './components/CTA.vue'
import Card from './components/Cards.vue'
import Cards from './components/Cards.vue'

export default {
  name: "App",
  components: {
    Navbar,
    Jumbotron,
    CTA,
    Cards,
    Cards
  }
}
</script>

<template>
  <Navbar />
  <Jumbotron />
  <CTA />
  <cards />
</template>

<style scoped>
</style>
