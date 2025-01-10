<template>
  <div class="text-4xl font-bold text-[#285A43] items-center text-center capitalize">
    <h1 class="">What we offer to you</h1>
  </div>

  <div class="container max-w-6xl px-6 py-12 mx-auto sm:px-8 lg:px-12">
    <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4">
      <div
        v-for="plant in plants.slice(0, 8)"
        :key="plant.name"
        class="relative w-full max-w-xs mx-auto"
      >
        <div class="bg-white rounded-md shadow-md">
          <!-- Image Section -->
          <div class="relative w-full aspect-square">
            <img
              :src="plant.image"
              :alt="plant.name"
              class="absolute object-cover w-full h-auto rounded-t-md"
            />
            <!-- Heart Icon -->
            <div
              class="absolute p-2 bg-white rounded-full cursor-pointer top-4 right-4"
              onclick="this.querySelector('svg path').setAttribute('fill', '#337A5B');"
            >
              <svg
                class="w-5 h-4 text-[#285A43] hover:fill-[#337A5B]"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"
                />
              </svg>
            </div>
          </div>
          <!-- Text Section -->
          <div class="p-2">
            <div class="flex items-center justify-between px-2 space-x-1">
              <div>
                <h3 class="text-[#337A5B] font-medium">Cactus Plant</h3>
                <span class="text-[80%]">
                  <span class="text-gray-400 line-through">($10)</span>
                  <span class="text-[#337A5B] font-medium ml-0.5">$8</span>
                </span>
              </div>
              <div class="">
                <button
                  class="px-4 py-1.5 border-2 text-xs hover:font-semibold border-[#337A5B]/60 text-[#337A5B] hover:bg-[#337A5B] hover:text-white rounded-sm transition-colors"
                >
                  Buy Now
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import p1 from '@/assets/offer/p1.png'
import p2 from '@/assets/offer/p2.png'
import p3 from '@/assets/offer/p3.png'
import p4 from '@/assets/offer/p4.png'
import p5 from '@/assets/offer/p5.png'
import p6 from '@/assets/offer/p6.png'
import p7 from '@/assets/offer/p7.png'
import p8 from '@/assets/offer/p8.png'
export default {
  data() {
    return {
      plants: [
        {
          image: p1,
          name: 'Cactus Plant',
          originalPrice: '10',
          price: '8',
        },
        {
          image: p2,
          name: 'Cactus Plant',
          originalPrice: '12',
          price: '9',
        },
        {
          image: p3,
          name: 'Cactus Plant',
          originalPrice: '10',
          price: '8',
        },
        {
          image: p4,
          name: 'Cactus Plant',
          originalPrice: '12',
          price: '9',
        },
        {
          image: p5,
          name: 'Cactus Plant',
          originalPrice: '10',
          price: '8',
        },
        {
          image: p6,
          name: 'Cactus Plant 2',
          originalPrice: '12',
          price: '9',
        },
        {
          image: p7,
          name: 'Cactus Plant',
          originalPrice: '10',
          price: '8',
        },
        {
          image: p8,
          name: 'Cactus Plant',
          originalPrice: '12',
          price: '9',
        },
      ],
    }
  },
}
</script>

<style></style>
