<template>
  <nav
    class="top-0 z-50 w-full flex flex-wrap items-center justify-between px-2 py-3"
  >
    <div
      class="container px-4 mx-auto flex flex-wrap items-center justify-between"
    >
      <div
        class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
      >
        <a href="/">
          <img
            src="/img/mlw_blk.png"
            alt="Moonlightwave Logo"
            class="w-72"
          /> </a
        ><button
          class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          v-on:click="toggleNavbar()"
        >
          <!-- <i class="text-white fas fa-bars"></i> -->
          <img src="/svg/menu_blk.svg" alt="Menu" class="w-4" />
        </button>
      </div>
      <div
        class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none"
        v-bind:class="{ hidden: !showMenu, block: showMenu }"
      >
        <ul class="flex flex-col lg:flex-row list-none mr-auto"></ul>
        <!-- // right menu -->
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <a
              class="lg:text-black lg:hover:text-pink-600 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="/#about"
              ><i
                class="lg:text-gray-300 text-gray-500 far fa-file-alt text-lg leading-lg mr-2"
              ></i>
              About</a
            >
          </li>

          <li class="flex items-center">
            <a
              class="lg:text-black lg:hover:text-pink-600 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="/#services"
              ><i
                class="lg:text-gray-300 text-gray-500 far fa-file-alt text-lg leading-lg mr-2"
              ></i>
              Services</a
            >
          </li>
          <li class="flex items-center">
            <a
              class="lg:text-black lg:hover:text-pink-600 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="/ceo"
              ><i
                class="lg:text-gray-300 text-gray-500 far fa-file-alt text-lg leading-lg mr-2"
              ></i>
              CEO</a
            >
          </li>
          <li class="flex items-center">
            <a
              class="lg:text-black lg:hover:text-pink-600 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="/#contact"
              ><i
                class="lg:text-gray-300 text-gray-500 far fa-file-alt text-lg leading-lg mr-2"
              ></i>
              Contact</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  data() {
    return {
      showMenu: false,
    };
  },
  methods: {
    toggleNavbar: function () {
      this.showMenu = !this.showMenu;
    },
  },
};
</script>
