<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HomeView from './views/HomeView.vue'
import SelectionView from './views/SelectionView.vue'
import OfferView from './views/OfferView.vue'
</script>

<template>
  <div class="w-screen">
    <HomeView> </HomeView>
    <SelectionView></SelectionView>
    <OfferView></OfferView>
  </div>
</template>

<style>
/* Reset default margins and padding */
body {
  margin: 0;
  padding: 0;
  width: 100vw;
  overflow-x: hidden;
}
</style>
