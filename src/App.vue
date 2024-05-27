<template>
  <q-layout>
    <navbar />
    <q-page-container>
      <carousel />
      <div class="q-pa-md">
        <q-card>
          <card />
        </q-card>
      </div>
    </q-page-container>
    <footer />
  </q-layout>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import Card from './components/Card.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    Navbar,
    Carousel,
    Card,
    Footer
  }
}
</script>
