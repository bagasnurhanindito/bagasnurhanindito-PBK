<template>
  <div class="q-pa-md">
    <q-carousel
      animated
      v-model="slide"
      arrows
      navigation
      infinite
    >
      <q-carousel-slide :name="1" img-src="../assets/nike airmax.jpg" />
      <q-carousel-slide :name="2" img-src="../assets/diskon.jpg" />
      <q-carousel-slide :name="3" img-src="../assets/ui.jpg" />
      <q-carousel-slide :name="4" img-src="../assets/data.jpg" />
    </q-carousel>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      slide: ref(1)
    }
  }
}
</script>
