<template>
  <q-card class="my-card">
    <img src="../assets/bagas.jpg">

    <q-card-section>
      <div class="text-h6">Adidas Samba</div>
      <div>Rp. 2.150.000</div>
    </q-card-section>

    <q-card-section class="q-pt-none">
      <q-btn flat label="Beli Sekarang" color="primary" />
        </q-card-section>
  </q-card>

  <q-card class="my-card">
    <img src="../assets/NB.jpg">

    <q-card-section>
      <div class="text-h6">New Balance 2002R</div>
      <div>Rp. 1.150.000</div>
    </q-card-section>

    <q-card-section class="q-pt-none">
      <q-btn flat label="Beli Sekarang" color="primary" />
        </q-card-section>
  </q-card>



    <q-card class="my-card">
      <img src="../assets/blazer.jpg">

      <q-card-section>
        <div class="text-h6">Nike Blazer</div>
        <div>Rp. 1.950.000</div>
      </q-card-section>
  
      <q-card-section>
        <q-btn flat label="Beli Sekarang" color="primary" />
      </q-card-section>
    </q-card>
  </template>
  
  <script>
  export default {
    name: 'Card'
  }
  </script>

<style lang="sass" scoped>
.my-card-container
  display: flex
  flex-wrap: nowrap
  justify-content: flex-start

.my-card
  flex: 0 0 auto
  width: 100%
  max-width: 250px
</style>



  