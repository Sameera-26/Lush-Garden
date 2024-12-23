<template>
  <div class="grid grid-cols-2 m-20">
    <div class="text-4xl font-bold text-[#285A43] items-left capitalize">
      <h1 class="">We Help choose the most</h1>
      <h1 class="">suitable plants for you</h1>
    </div>
    <div class="text-lg font-normal text-[#285A43] items-left capitalize">
      Our selection includes a wide variety of flowers, from classic roses to exotic orchids, as
      well as a variety of lush indoor and outdoor plants and also offer unique floral arrangements
      that are perfect for any occasion, whether you're looking to brighten up your home or send a
      thoughtful gift.
    </div>
  </div>
  <div class="grid grid-cols-3 m-20 gap-6 mt-12">
    <div
      class="block max-w-sm p-12 max-h-lg bg-white border border-gray-200/5 rounded-lg shadow-xl hover:bg-[#337A5B] hover:shadow-lg dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 hover:text-white"
    >
      <img src="@/assets/Indoor_Plant.png" alt="Indoor Plants" class="py-6 transition-all" />
      <h5 class="mb-2 text-xl font-semibold tracking-tight text-[#285A43] dark:text-white">
        Indoor Plants
      </h5>
      <p class="font-normal text-lg text-left text-gray-700 dark:text-gray-400">
        Bring the beauty of nature to your outdoor spaces with our wide selection of outdoor plants
      </p>
    </div>
    <div
      class="block max-w-sm p-12 max-h-lg bg-white border border-gray-200/5 rounded-lg shadow-xl hover:bg-[#337A5B] hover:shadow-lg dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 hover:text-white"
    >
      <img src="@/assets/Outdoor_Plant.png" alt="Indoor Plants" class="py-6 transition-all" />
      <h5 class="mb-2 text-xl font-semibold tracking-tight text-[#285A43] dark:text-white">
        Outdoor Plants
      </h5>
      <p class="font-normal text-lg text-left text-gray-700 dark:text-gray-400">
        Bring a touch of greenery to your living spaces with our collection of indoor plants,
        perfect for purifying the air and adding a natural touch to your home.
      </p>
    </div>
    <div
      class="block max-w-sm p-12 max-h-lg bg-white border border-gray-200/5 rounded-lg shadow-xl hover:bg-[#337A5B] hover:shadow-lg dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 hover:text-white"
    >
      <img src="@/assets/Bamboo.png" alt="Indoor Plants" class="py-6 transition-all" />
      <h5 class="mb-2 text-xl font-semibold tracking-tight text-[#285A43] dark:text-white">
        Plants Pots
      </h5>
      <p class="font-normal text-lg text-left text-gray-700 dark:text-gray-400">
        Add a touch of style to your indoor or outdoor spaces with our collection of pots plants,
        available in a variety of sizes and designs to fit any decor
      </p>
    </div>
  </div>
</template>

<style scoped>
/* Ensure text color change on hover inside the card */
.block:hover h5,
.block:hover p {
  color: white;
}
/* Make the image white on hover */
.block:hover img {
  filter: brightness(0) invert(1); /* Makes the image white */
}
</style>
