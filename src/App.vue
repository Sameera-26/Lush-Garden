<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HomeView from './views/HomeView.vue'
import SelectionView from './views/SelectionView.vue'
import OfferView from './views/OfferView.vue'
import BenefitView from './views/BenefitView.vue'
import ReviewView from './views/ReviewView.vue'
import BlogView from './views/BlogView.vue'
import Footer from './Layout/Footer.vue'
</script>

<template>
  <div class="w-screen">
    <HomeView> </HomeView>
    <SelectionView></SelectionView>
    <OfferView></OfferView>
    <BenefitView></BenefitView>
    <ReviewView></ReviewView>
    <BlogView></BlogView>
    <Footer></Footer>
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
