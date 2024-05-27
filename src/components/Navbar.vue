<template>
  <div class="q-pa-md">
    <q-layout view="lHh lpr lFf" container style="height: 250px" class="shadow-2 rounded-borders">
      <q-header elevated class="bg-cyan">
        <q-toolbar>
          <q-btn flat round dense icon="assignment_ind" />
          <q-toolbar-title>ONLINE STORE BAGAS</q-toolbar-title>

          <q-space />

          <q-btn flat round dense icon="sim_card" class="q-mr-xs" />
          <q-btn flat round dense icon="gamepad" />
        </q-toolbar>

        <q-toolbar inset>
          <q-breadcrumbs active-color="white" style="font-size: 16px">
            <q-breadcrumbs-el to="/" label="Home" />
            <q-breadcrumbs-el to="/products" label="Products" />
            <q-breadcrumbs-el label="Sepatu" />
          </q-breadcrumbs>
        </q-toolbar>
      </q-header>

      <q-page-container>
        <q-page class="q-pa-md">
          <p v-for="n in 1" :key="n" class="promo-text">
            Ayo beli sepatu disini dijamin puas!!!!!! Diskon banyak DIJAMIN ORIIII
          </p>
        </q-page>
      </q-page-container>
    </q-layout>
  </div>
</template>

<script>
export default {
  name: 'OnlineStoreBagas',
};
</script>

<style>
.promo-text {
  font-size: 40px;
  font-weight: bold;
  color: #161313; 
  text-align: center;
  margin: 20px 0;
  background-color: #f0f8ff; 
  padding: 10px; 
  border-radius: 10px; 
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
}
</style>
