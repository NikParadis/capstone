<template>
  <div class="mt-12 mb-4 p-8 md:p-12">
    <h1 class="text-4xl font-semibold">Team</h1>
    <p
      class="text-xl leading-relaxed"
    >Deciding to live together through Covid-19 definitely made group formation easy. Having a complimentary skillset also worked out well. Feel free to send us a message, for whatever reason, via email or LinkedIn!</p>
    <nuxt-link to="/blog">
      <button
        class="rounded-lg px-10 my-4 py-3 bg-red-600 hover:bg-red-700 text-white font-semibold relative"
      >
        See what we're up to
        <span class="flex h-3 w-3 absolute right-0" style="top: -5px">
          <span class="animate-ping absolute h-4 w-4 rounded-full bg-red-400 opacity-75"></span>
          <span class="absolute inline-flex rounded-full h-4 w-4 bg-red-500"></span>
        </span>
      </button>
    </nuxt-link>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 xl:grid-cols-4 gap-4 mt-3">
      <!-- new person -->
      <div class="max-w-sm bg-white shadow-lg rounded-lg overflow-hidden my-4">
        <img class="w-full h-56 object-cover object-center" :src="`${nik}`" alt="Nik Paradis" />
        <div class="flex items-center px-6 py-3 bg-gray-900">
          <svg class="h-6 w-6 text-white fill-current" viewBox="0 0 512 512">
            <g id="XMLID_24_">
              <path
                id="XMLID_313_"
                d="m338.029 370.441c1.054.084 2.115.141 3.19.141 23.617 0 42.762-20.674 42.762-46.176 0-10.037-2.975-19.318-8.012-26.894 11.625-8.254 19.305-22.456 19.305-38.603 0-19.465-11.158-36.104-26.94-42.898 1.164-4.2 1.798-8.647 1.798-13.256 0-24.624-17.85-44.74-40.339-46.098-2.474-19.519-17.967-34.56-36.723-34.56-8.206 0-15.871 2.883-22.107 7.756v247.227c8.112 7.964 18.887 12.82 30.715 12.82 14.831.002 28.005-7.635 36.351-19.459z"
              />
              <path
                id="XMLID_312_"
                d="m241.037 130.002c-6.173-4.961-13.821-7.903-22.108-7.903-18.755 0-34.248 15.041-36.723 34.56-22.489 1.358-40.339 21.474-40.339 46.098 0 4.609.634 9.056 1.797 13.256-15.781 6.794-26.939 23.433-26.939 42.898 0 16.146 7.68 30.349 19.305 38.603-5.036 7.575-8.012 16.856-8.012 26.894 0 25.503 19.145 46.176 42.762 46.176 1.075 0 2.136-.057 3.19-.141 8.346 11.824 21.52 19.46 36.35 19.46 11.828 0 22.604-4.856 30.716-12.821v-247.08z"
              />
              <path
                id="XMLID_311_"
                d="m53.771 201.336c19.339-71.107 75.448-127.27 146.623-146.835-2.689-6.785-4.184-14.168-4.184-21.897 0-2.778.207-5.508.576-8.187-41.298 10.436-79.174 31.797-110.085 62.635-30.837 30.764-52.218 68.444-62.711 109.531 1.904-.183 3.832-.284 5.784-.284 8.532.001 16.646 1.807 23.997 5.037z"
              />
              <path
                id="XMLID_310_"
                d="m53.771 310.664c-7.351 3.23-15.465 5.036-23.997 5.036-1.952 0-3.88-.101-5.784-.284 10.493 41.088 31.875 78.768 62.712 109.532 30.911 30.838 68.787 52.198 110.085 62.634-.37-2.678-.576-5.408-.576-8.187 0-7.729 1.495-15.112 4.184-21.897-71.176-19.565-127.285-75.727-146.624-146.834z"
              />
              <path
                id="XMLID_309_"
                d="m458.229 201.336c7.351-3.23 15.465-5.037 23.998-5.037 1.951 0 3.879.101 5.783.284-10.493-41.088-31.875-78.767-62.711-109.531-30.911-30.839-68.786-52.199-110.085-62.635.37 2.679.576 5.409.576 8.187 0 7.729-1.495 15.112-4.184 21.897 71.175 19.565 127.284 75.728 146.623 146.835z"
              />
              <path
                id="XMLID_70_"
                d="m458.229 310.664c-19.339 71.107-75.449 127.27-146.623 146.835 2.689 6.785 4.184 14.168 4.184 21.897 0 2.778-.207 5.508-.576 8.187 41.298-10.436 79.173-31.796 110.085-62.634 30.837-30.764 52.219-68.444 62.712-109.532-1.905.184-3.832.284-5.784.284-8.533-.001-16.647-1.807-23.998-5.037z"
              />
              <path
                id="XMLID_45_"
                d="m256 62.378c16.443 0 29.773-13.33 29.773-29.774 0-16.443-13.33-29.774-29.773-29.774-16.444 0-29.774 13.33-29.774 29.774s13.331 29.774 29.774 29.774z"
              />
              <path
                id="XMLID_44_"
                d="m482.227 226.227c-16.444 0-29.774 13.33-29.774 29.774 0 16.443 13.33 29.774 29.774 29.774 16.443-.001 29.773-13.331 29.773-29.775s-13.33-29.773-29.773-29.773z"
              />
              <path
                id="XMLID_43_"
                d="m59.547 256c0-16.444-13.33-29.774-29.773-29.774-16.444.001-29.774 13.33-29.774 29.774 0 16.443 13.33 29.774 29.774 29.774 16.443 0 29.773-13.33 29.773-29.774z"
              />
              <path
                id="XMLID_8_"
                d="m256 449.622c-16.444 0-29.774 13.33-29.774 29.774 0 16.443 13.33 29.774 29.774 29.774 16.443 0 29.773-13.33 29.773-29.774.001-16.444-13.33-29.774-29.773-29.774z"
              />
            </g>
          </svg>
          <h1 class="mx-3 text-white font-semibold text-lg">Product</h1>
        </div>
        <div class="py-4 px-6">
          <h1 class="text-2xl font-semibold text-gray-800">Nik Paradis</h1>
          <p
            class="py-2 text-lg text-gray-700"
          >Stock market oracle. Coordinates some team stuff. WSB degenerate.</p>
          <div class="flex items-center mt-4 text-gray-700">
            <a
              class="flex align-center"
              href="https://www.linkedin.com/in/nikparadis/"
              target="_blank"
            >
              <svg class="h-6 w-6 fill-current" viewBox="0 0 26 26">
                <path
                  d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                />
              </svg>
              <h1 class="px-2 text-sm">Nik's LinkedIn</h1>
            </a>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M256 32c-88.004 0-160 70.557-160 156.801C96 306.4 256 480 256 480s160-173.6 160-291.199C416 102.557 344.004 32 256 32zm0 212.801c-31.996 0-57.144-24.645-57.144-56 0-31.357 25.147-56 57.144-56s57.144 24.643 57.144 56c0 31.355-25.148 56-57.144 56z"
              />
            </svg>
            <h1 class="px-2 text-sm">Waterloo</h1>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M437.332 80H74.668C51.199 80 32 99.198 32 122.667v266.666C32 412.802 51.199 432 74.668 432h362.664C460.801 432 480 412.802 480 389.333V122.667C480 99.198 460.801 80 437.332 80zM432 170.667L256 288 80 170.667V128l176 117.333L432 128v42.667z"
              />
            </svg>
            <h1 class="px-2 text-sm">nparadis@uwaterloo.ca</h1>
          </div>
        </div>
      </div>
      <!-- new person -->
      <div class="max-w-sm bg-white shadow-lg rounded-lg overflow-hidden my-4">
        <img class="w-full h-56 object-cover object-center" :src="`${aidan}`" alt="Aidan Barry" />
        <div class="flex items-center px-6 py-3 bg-gray-900">
          <svg class="h-6 w-6 text-white fill-current" viewBox="0 0 32 32">
            <path
              d="M32,17.969v-4l-4.781-1.992c-0.133-0.375-0.273-0.738-0.445-1.094l1.93-4.805L25.875,3.25 l-4.762,1.961c-0.363-0.176-0.734-0.324-1.117-0.461L17.969,0h-4l-1.977,4.734c-0.398,0.141-0.781,0.289-1.16,0.469l-4.754-1.91 L3.25,6.121l1.938,4.711C5,11.219,4.848,11.613,4.703,12.02L0,14.031v4l4.707,1.961c0.145,0.406,0.301,0.801,0.488,1.188 l-1.902,4.742l2.828,2.828l4.723-1.945c0.379,0.18,0.766,0.324,1.164,0.461L14.031,32h4l1.98-4.758 c0.379-0.141,0.754-0.289,1.113-0.461l4.797,1.922l2.828-2.828l-1.969-4.773c0.168-0.359,0.305-0.723,0.438-1.094L32,17.969z M15.969,22c-3.312,0-6-2.688-6-6s2.688-6,6-6s6,2.688,6,6S19.281,22,15.969,22z"
            />
          </svg>
          <h1 class="mx-3 text-white font-semibold text-lg">Mechanical</h1>
        </div>
        <div class="py-4 px-6">
          <h1 class="text-2xl font-semibold text-gray-800">Aidan Barry</h1>
          <p
            class="py-2 text-lg text-gray-700"
          >Catch me on the slopes. Making sure our solids work. Pow is my middle name.</p>
          <div class="flex items-center mt-4 text-gray-700">
            <a
              class="flex align-center"
              href="https://www.linkedin.com/in/aidan-barry/"
              target="_blank"
            >
              <svg class="h-6 w-6 fill-current" viewBox="0 0 26 26">
                <path
                  d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                />
              </svg>
              <h1 class="px-2 text-sm">Aidan's LinkedIn</h1>
            </a>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M256 32c-88.004 0-160 70.557-160 156.801C96 306.4 256 480 256 480s160-173.6 160-291.199C416 102.557 344.004 32 256 32zm0 212.801c-31.996 0-57.144-24.645-57.144-56 0-31.357 25.147-56 57.144-56s57.144 24.643 57.144 56c0 31.355-25.148 56-57.144 56z"
              />
            </svg>
            <h1 class="px-2 text-sm">Vancouver</h1>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M437.332 80H74.668C51.199 80 32 99.198 32 122.667v266.666C32 412.802 51.199 432 74.668 432h362.664C460.801 432 480 412.802 480 389.333V122.667C480 99.198 460.801 80 437.332 80zM432 170.667L256 288 80 170.667V128l176 117.333L432 128v42.667z"
              />
            </svg>
            <h1 class="px-2 text-sm">apbarry@uwaterloo.ca</h1>
          </div>
        </div>
      </div>
      <!-- new person -->
      <div class="max-w-sm bg-white shadow-lg rounded-lg overflow-hidden my-4">
        <img class="w-full h-56 object-cover object-center" :src="`${mitch}`" alt="Mitch Voralek" />
        <div class="flex items-center px-6 py-3 bg-gray-900">
          <svg class="h-6 w-6 text-white fill-current" viewBox="0 0 32 32">
            <path
              d="M32,17.969v-4l-4.781-1.992c-0.133-0.375-0.273-0.738-0.445-1.094l1.93-4.805L25.875,3.25 l-4.762,1.961c-0.363-0.176-0.734-0.324-1.117-0.461L17.969,0h-4l-1.977,4.734c-0.398,0.141-0.781,0.289-1.16,0.469l-4.754-1.91 L3.25,6.121l1.938,4.711C5,11.219,4.848,11.613,4.703,12.02L0,14.031v4l4.707,1.961c0.145,0.406,0.301,0.801,0.488,1.188 l-1.902,4.742l2.828,2.828l4.723-1.945c0.379,0.18,0.766,0.324,1.164,0.461L14.031,32h4l1.98-4.758 c0.379-0.141,0.754-0.289,1.113-0.461l4.797,1.922l2.828-2.828l-1.969-4.773c0.168-0.359,0.305-0.723,0.438-1.094L32,17.969z M15.969,22c-3.312,0-6-2.688-6-6s2.688-6,6-6s6,2.688,6,6S19.281,22,15.969,22z"
            />
          </svg>
          <h1 class="mx-3 text-white font-semibold text-lg">Mechanical</h1>
        </div>
        <div class="py-4 px-6">
          <h1 class="text-2xl font-semibold text-gray-800">Mitch Voralek</h1>
          <p
            class="py-2 text-lg text-gray-700"
          >Feared Warzone player. Run some simulations ftb. Sponsored by Pabst.</p>
          <div class="flex items-center mt-4 text-gray-700">
            <a
              class="flex align-center"
              href="https://www.linkedin.com/in/mitch-voralek-593560140/"
              target="_blank"
            >
              <svg class="h-6 w-6 fill-current" viewBox="0 0 26 26">
                <path
                  d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                />
              </svg>
              <h1 class="px-2 text-sm">Mitch's LinkedIn</h1>
            </a>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M256 32c-88.004 0-160 70.557-160 156.801C96 306.4 256 480 256 480s160-173.6 160-291.199C416 102.557 344.004 32 256 32zm0 212.801c-31.996 0-57.144-24.645-57.144-56 0-31.357 25.147-56 57.144-56s57.144 24.643 57.144 56c0 31.355-25.148 56-57.144 56z"
              />
            </svg>
            <h1 class="px-2 text-sm">Waterloo</h1>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M437.332 80H74.668C51.199 80 32 99.198 32 122.667v266.666C32 412.802 51.199 432 74.668 432h362.664C460.801 432 480 412.802 480 389.333V122.667C480 99.198 460.801 80 437.332 80zM432 170.667L256 288 80 170.667V128l176 117.333L432 128v42.667z"
              />
            </svg>
            <h1 class="px-2 text-sm">mavorale@uwaterloo.ca</h1>
          </div>
        </div>
      </div>
      <!-- new person -->
      <div class="max-w-sm bg-white shadow-lg rounded-lg overflow-hidden my-4">
        <img class="w-full h-56 object-cover object-center" :src="`${john}`" alt="John Tattersall" />
        <div class="flex items-center px-6 py-3 bg-gray-900">
          <svg class="h-6 w-6 text-white fill-current" viewBox="0 0 192 192">
            <path
              d="m155.109 74.028a4 4 0 0 0 -3.48-2.028h-52.4l8.785-67.123a4.023 4.023 0 0 0 -7.373-2.614l-63.724 111.642a4 4 0 0 0 3.407 6.095h51.617l-6.962 67.224a4.024 4.024 0 0 0 7.411 2.461l62.671-111.63a4 4 0 0 0 .048-4.027z"
            />
          </svg>
          <h1 class="mx-3 text-white font-semibold text-lg">Electrical</h1>
        </div>
        <div class="py-4 px-6">
          <h1 class="text-2xl font-semibold text-gray-800">John Tattersall</h1>
          <p
            class="py-2 text-lg text-gray-700"
          >Best ADC NA. Some call him Triplelift. Ensuring house will not catch on fire.</p>
          <div class="flex items-center mt-4 text-gray-700">
            <a
              class="flex align-center"
              href="https://www.linkedin.com/in/john-tattersall-b53932117/"
              target="_blank"
            >
              <svg class="h-6 w-6 fill-current" viewBox="0 0 26 26">
                <path
                  d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                />
              </svg>
              <h1 class="px-2 text-sm">John's LinkedIn</h1>
            </a>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M256 32c-88.004 0-160 70.557-160 156.801C96 306.4 256 480 256 480s160-173.6 160-291.199C416 102.557 344.004 32 256 32zm0 212.801c-31.996 0-57.144-24.645-57.144-56 0-31.357 25.147-56 57.144-56s57.144 24.643 57.144 56c0 31.355-25.148 56-57.144 56z"
              />
            </svg>
            <h1 class="px-2 text-sm">Waterloo</h1>
          </div>
          <div class="flex items-center mt-4 text-gray-700">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
              <path
                d="M437.332 80H74.668C51.199 80 32 99.198 32 122.667v266.666C32 412.802 51.199 432 74.668 432h362.664C460.801 432 480 412.802 480 389.333V122.667C480 99.198 460.801 80 437.332 80zM432 170.667L256 288 80 170.667V128l176 117.333L432 128v42.667z"
              />
            </svg>
            <h1 class="px-2 text-sm">jatatter@uwaterloo.ca</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      aidan: require("@/assets/aidan.jpg"),
      nik: require("@/assets/nik.jpg"),
      mitch: require("@/assets/mitch.jpg"),
      john: require("@/assets/john.jpg")
    };
  },
  transition: "fade"
};
</script>