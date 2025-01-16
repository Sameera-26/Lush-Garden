<template>
  <div>
    <div class="relative bg-[#285A43]">
      <!-- Left plant outline -->
      <div class="absolute bottom-0 left-0 opacity-20">
        <img src="@/assets/blog/Monstera.png" alt="Monstera leaf outline" class="object-contain" />
      </div>

      <!-- Right plant outline -->
      <div class="absolute bottom-0 right-0 opacity-20">
        <img src="@/assets/blog/Fern.png" alt="Fern leaf outline" class="object-contain" />
      </div>

      <div
        class="z-10 items-center justify-center py-16 text-3xl font-semibold leading-10 text-center text-white capitalize"
      >
        Feel free to contact us
        <div class="flex items-center justify-center gap-20 my-8">
          <a
            href="https://www.instagram.com/turingoid"
            class="p-0 rounded-full"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="@/assets/blog/Facebook.png" alt="facebook" class="size-lg" />
          </a>
          <a
            href="https://www.instagram.com/turingoid"
            class="p-0 rounded-full"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="@/assets/blog/Instagram.png" alt="instagram" />
          </a>
          <a
            href="https://www.x.com/turingoid"
            class="p-0 rounded-full"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="@/assets/blog/Twitter.png" alt="twitter" />
          </a>
        </div>

        <div class="flex items-center justify-center gap-20 my-8">
          <div class="text-lg">Home</div>
          <div class="text-lg">About Us</div>
          <div class="text-lg">Plants</div>
          <div class="text-lg">Delivery</div>
          <div class="text-lg">Blog</div>
          <div class="text-lg">Contact Us</div>
        </div>
      </div>
    </div>

    <a href="https://turingoid.com" class="p-0" target="_blank" rel="noopener noreferrer">
      <div class="py-2 text-center bg-black">
        <div class="text-white text-md">Copyright © 2024 Turingoid. All rights reserved.</div>
      </div>
    </a>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
