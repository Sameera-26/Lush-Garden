<template>
  <div class="bg-[url('@/assets/hero.png')] h-screen w-screen bg-cover bg-center bg-no-repeat">
    <Main></Main>
    <div class="flex flex-col items-center justify-center py-12 my-11">
      <h1 class="text-6xl font-semibold text-white">Nature's Beauty Delivered to You</h1>
      <div class="py-12">
        <h3
          class="text-sm font-normal text-center text-white lg:text-xl md:text-xl sm:text-xl text-pretty"
        >
          Nature's beauty is just a click away with our online flower and plant shop. We offer wide
        </h3>
        <h3
          class="text-sm font-normal text-center text-white lg:text-xl md:text-xl sm:text-xl text-pretty"
        >
          a wide variety of flowers that will bring a touch of nature to your home!
        </h3>
      </div>
      <div class="flex flex-row">
        <a href="https://turingoid.com" class="p-0" target="_blank" rel="noopener noreferrer">
          <button
            class="border-2 rounded-sm text-white px-6 lg:px-12 py-2 bg-[#285A43] hover:bg-white/20 hover:text-[#285A43] hover:font-semibold border-[#285A43]"
          >
            Book Now
          </button>
        </a>
        <a href="https://turingoid.com" class="p-0" target="_blank" rel="noopener noreferrer">
          <button
            class="border-2 rounded-sm flex text-white mx-7 px-6 lg:px-12 py-2 hover:bg-[#285A43]/40 hover:border-[#285A43]/40"
          >
            <img class="mx-2" src="@/assets/play.png" />
            Watch Video
          </button>
        </a>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
import Main from '@/Layout/Main.vue'
</script>
