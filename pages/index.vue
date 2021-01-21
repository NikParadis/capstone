<template>
  <div v-if="!isMobile">
    <div class="w-full relative fade-in" style="top:58px">
      <img
        :src="`${banner}`"
        class="object-right"
        style="width: 100%; min-height: 450px; position: relative"
      />
      <div
        class="absolute leading-relaxed h-5/6 w-4/12 text-2xl"
        style="top: 10%; left: 5%; font-size: calc(1rem + 0.4vw)"
      >
        <h1 class="font-bold text-5xl">Hot Knife</h1>
        <p>
          A power tool that harnesses the power of heat, creating a low-noise, mess-free working environment. Optimized for
          <a
            class="text-red-600 hover:text-red-700"
            href="https://trusscore.com/"
            target="_blank"
          >Trusscore</a> panels, we're helping with the revolution to sustainable building materials.
        </p>
        <nuxt-link to="team">
          <button
            class="rounded-lg px-10 mt-6 py-3 bg-red-600 hover:bg-red-700 text-white font-medium relative"
          >
            Meet the team
            <span class="flex h-3 w-3 absolute right-0" style="top: -5px">
              <span class="animate-ping absolute h-4 w-4 rounded-full bg-red-400 opacity-75"></span>
              <span class="absolute inline-flex rounded-full h-4 w-4 bg-red-500"></span>
            </span>
          </button>
        </nuxt-link>
      </div>
    </div>
  </div>

  <div v-else>
    <div class="w-full relative fade-in" style="top:58px">
      <img :src="`${mobileBanner}`" class="w-full relative" />
      <div class="relative leading-relaxed w-full p-8 text-2xl">
        <h1 class="font-bold text-4xl">Hot Knife</h1>
        <p>
          A power tool that harnesses the power of heat, creating a low-noise, mess-free working environment. Optimized for
          <a
            class="text-red-600 hover:text-red-700"
            href="https://trusscore.com/"
            target="_blank"
          >Trusscore</a> panels, we're helping with the revolution to sustainable building materials.
        </p>
        <nuxt-link to="team">
          <button
            class="rounded-lg px-10 my-6 py-3 bg-red-600 hover:bg-red-700 text-white font-medium relative"
          >
            Meet the team
            <span class="flex h-3 w-3 absolute right-0" style="top: -5px">
              <span class="animate-ping absolute h-4 w-4 rounded-full bg-red-400 opacity-75"></span>
              <span class="absolute inline-flex rounded-full h-4 w-4 bg-red-500"></span>
            </span>
          </button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      banner: require("@/assets/render1.jpg"),
      mobileBanner: require("@/assets/render1mobile.jpg"),
      isMobile: false
    };
  },
  mounted() {
    const w = window.innerWidth;
    this.isMobile = w < 750;
    window.addEventListener("resize", () => {
      const w = window.innerWidth;
      this.isMobile = w < 750;
    });
  },
  transition: "fade"
};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.fade-in {
  opacity: 1;
  animation-name: fadeInOpacity;
  animation-iteration-count: 1;
  animation-timing-function: ease-in;
  animation-duration: 1s;
}

@keyframes fadeInOpacity {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
