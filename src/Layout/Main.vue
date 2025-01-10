<template>
  <div class="flex flex-wrap items-center justify-between max-w-screen-xl p-2 mx-auto">
    <img class="px-8 my-5" src="@/assets/logo.png" style="max-width-100%" />

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
        <button class="border-2 rounded-sm hover:bg-[#285A43]/20 text-white mx-7 px-14">
          Call Us
        </button>
      </ul>
    </div>
    <!-- Hamburger Button for Mobile -->
    <button @click="toggleMenu" class="text-white md:hidden focus:outline-none">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        class="w-6 h-6"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M4 6h16M4 12h16M4 18h16"
        />
      </svg>
    </button>

    <!-- Navigation Links -->
    <div
      :class="{
        block: isMenuOpen,
        hidden: !isMenuOpen,
        'md:flex': true,
        'relative top-full left-0 w-full bg-transparent text-center': true,
      }"
    >
      <ul
        :class="{
          'flex flex-col p-4 md:p-0 mt-4 border md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0': true,
          block: isMenuOpen, // Show menu if open
          hidden: !isMenuOpen, // Hide menu if closed
        }"
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
        <button
          class="border-2 rounded-sm bg-[#285A43]/20 md:hover:bg-[#285A43]/20 text-white md:mx-7 px-14"
        >
          Call Us
        </button>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false, // State to toggle menu visibility
    }
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen
    },
  },
}
</script>
