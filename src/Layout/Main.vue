<template>
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-2">
    <img class="my-5 px-8" src="@/assets/logo.png" />
  </div>
  <div class="hidden w-full md:block md:w-auto">
    <ul
      class="font-medium flex flex-col p-4 md:p-0 mt-4 border md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0"
    >
      <li>
        <a
          href="#"
          class="block py-2 px-3 text-lg text-white hover:underline hover:decoration-1.5 hover:underline-offset-4"
          aria-current="page"
          >Home</a
        >
      </li>
      <li>
        <a
          href="#"
          class="block py-2 px-3 text-lg text-white hover:underline hover:decoration-1.5 hover:underline-offset-4"
          aria-current="page"
          >About Us</a
        >
      </li>
      <li>
        <a
          href="#"
          class="block py-2 px-3 text-lg text-white hover:underline hover:decoration-1.5 hover:underline-offset-4"
          aria-current="page"
          >Planters</a
        >
      </li>
      <li>
        <a
          href="#"
          class="block py-2 px-3 text-lg text-white hover:underline hover:decoration-1.5 hover:underline-offset-4"
          aria-current="page"
          >Contact</a
        >
      </li>
      <button class="border-2 rounded-sm text-white mx-7 px-14">Call Us</button>
    </ul>
  </div>
  <!-- Route Content Placeholder -->
  <router-view />
</template>

<script>
export default {}
</script>

<style></style>
