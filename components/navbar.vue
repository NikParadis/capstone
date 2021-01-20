<template>
  <!-- container for fixed nav bar -->
  <div class="fixed z-50 w-full top-0" ref="navbar">
    <header class="lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 py-2 shadow-sm">
      <div class="flex-1 flex justify-between items-center">
        <a href="#">
          <!-- <img
            src="./images/vatLogo.svg"
            width="32px"
            height="32px"
            alt="Vat Corp Logo"
            style="float: left"
          />-->
          <h1 class="font-medium text-2xl ml-3" style="float: left">
            <span class="py-2 md:py-3 border-b-2 border-transparent hover:border-red-400">Vat Corp</span>
          </h1>
        </a>
      </div>

      <label for="menu-toggle" class="cursor-pointer lg:hidden block">
        <svg
          class="fill-current text-gray-900"
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 20 20"
        >
          <title>menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </label>
      <input class="hidden" type="checkbox" id="menu-toggle" />

      <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
        <nav>
          <ul class="lg:flex items-center justify-between text-base text-gray-700 pt-4 lg:pt-0">
            <li>
              <a
                class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-blue-400"
                href="#clients"
              >Clients</a>
            </li>
            <li>
              <a
                class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-green-400"
                href="#contact"
              >Contact</a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  mounted: function() {
    const height = this.$refs.navbar.clientHeight;
    console.log(height);
  }
};
</script>

<style>
#menu-toggle:checked + #menu {
  display: block;
}
html {
  scroll-behavior: smooth;
}
</style>