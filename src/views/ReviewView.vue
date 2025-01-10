<template>
  <div class="text-4xl font-bold text-[#285A43] items-center text-center capitalize my-10">
    <h1 class="">What do they say about Us</h1>
  </div>
  <div
    class="grid justify-center grid-cols-1 gap-6 m-5 mt-6 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 sm:m-6 md:m-20 lg:m-20"
  >
    <div
      class="my-10 relative block max-w-sm p-6 bg-[#F8F8F8] border border-[#F8F8F8] rounded-lg dark:bg-gray-800 dark:border-gray-700"
    >
      <!-- Background Image -->
      <div
        class="absolute bg-[url('@/assets/review/Plant.png')] inset-x-0 bottom-0 bg-right-bottom bg-no-repeat bg-contain h-[70%]"
      ></div>

      <!-- Content -->
      <div class="relative p-6">
        <div class="flex items-center mb-4">
          <img src="@/assets/review/Doris.png" alt="Doris Watson" class="w-12 h-12 rounded-full" />
          <h5 class="ml-4 text-xl font-raleway font-semibold text-[#285A43] dark:text-white">
            Doris Watson
          </h5>
        </div>
        <p
          class="leading-6 mr-12 font-raleway text-lg font-light text-[#121212] dark:text-gray-300"
        >
          “ Highly recommend this website for quality flowers and plants. Great prices, timely
          delivery and excellent customer service. ”
        </p>
      </div>
    </div>
    <div
      class="my-10 relative block max-w-sm p-6 bg-[#F8F8F8] border border-[#F8F8F8] rounded-lg dark:bg-gray-800 dark:border-gray-700"
    >
      <!-- Background Image -->
      <div
        class="absolute bg-[url('@/assets/review/Snake-Plant.png')] inset-x-0 bottom-0 bg-right-bottom bg-no-repeat bg-contain h-[70%]"
      ></div>

      <!-- Content -->
      <div class="relative p-6">
        <div class="flex items-center mb-4">
          <img src="@/assets/review/Kat.png" alt="Doris Watson" class="w-12 h-12 rounded-full" />
          <h5 class="ml-4 text-xl font-raleway font-semibold text-[#285A43] dark:text-white">
            Doris Watson
          </h5>
        </div>
        <p
          class="leading-6 mr-10 font-raleway text-lg font-light text-[#121212] dark:text-gray-300"
        >
          "Great service, beautiful flowers, timely delivery. Highly recommend."
        </p>
      </div>
    </div>
    <div
      class="my-10 relative block max-w-sm p-6 bg-[#F8F8F8] border border-[#F8F8F8] rounded-lg dark:bg-gray-800 dark:border-gray-700"
    >
      <!-- Background Image -->
      <div
        class="absolute bg-[url('@/assets/review/Bamboo.png')] inset-x-0 bottom-0 bg-right-bottom bg-no-repeat bg-contain h-[70%]"
      ></div>

      <!-- Content -->
      <div class="relative p-6">
        <div class="flex items-center mb-4">
          <img src="@/assets/review/Dyness.png" alt="Doris Watson" class="w-12 h-12 rounded-full" />
          <h5 class="ml-4 text-xl font-raleway font-semibold text-[#285A43] dark:text-white">
            Doris Watson
          </h5>
        </div>
        <p
          class="leading-6 mr-12 font-raleway text-lg font-light text-[#121212] dark:text-gray-300"
        >
          "I am very happy with my purchase from this website, the plants were healthy and arrived
          on time.”
        </p>
      </div>
    </div>
  </div>
  <div class="relative h-[300px] w-full overflow-hidden">
    <!-- Background image with overlay -->
    <div class="absolute inset-0">
      <img
        src="@/assets/review/email.png"
        alt="Nature background"
        class="object-cover w-full h-full"
      />
      <div class="absolute inset-0 bg-black/30"></div>
      <!-- Dark overlay -->
    </div>

    <!-- Content -->
    <div class="relative z-10 flex flex-row items-center justify-center h-full p-6 text-white">
      <h2 class="max-w-md p-4 mt-6 text-2xl font-normal leading-10 justify-left">
        Enter Your Email Address For Our Mailing Promo Or Other Interesting Things
      </h2>

      <!-- Email input form -->
      <div class="flex w-full max-w-md gap-2">
        <input
          type="email"
          placeholder="Enter your email"
          class="flex-1 px-4 py-2 text-white bg-transparent border rounded-md"
        />
        <button
          class="px-8 py-2 bg-[#2F5D4B] hover:text-[#2F5D4B] text-white font-normal rounded-md hover:bg-white"
        >
          Submit
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
