<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HomeView from './views/HomeView.vue'
import AboutView from './views/AboutView.vue'
</script>

<template>
  <div class="flex flex-col">
    <HomeView> </HomeView>
    <AboutView></AboutView>
  </div>
</template>

<style scoped></style>
