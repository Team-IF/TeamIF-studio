<template>
  <nav
    class="flex items-center justify-between flex-wrap bg-black bg-opacity-75 p-6"
  >
    <div class="flex items-center flex-shrink-0 text-white mr-6">
      <nuxt-link to="/" class="font-semibold text-xl tracking-tight"
        >TeamIF Studio</nuxt-link
      >
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-white border-white hover:text-white hover:border-white"
        @click="toggleMenu = !toggleMenu"
      >
        <svg
          class="fill-current h-3 w-3"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div
      v-show="toggleMenu"
      class="w-full block flex-grow lg:flex lg:items-center lg:w-auto"
    >
      <div class="text-md text-white lg:flex-grow">
        <nuxt-link
          to="/deeper-world"
          class="block mt-4 lg:inline-block lg:mt-0 hover:text-gray-300 mr-4 text-md"
        >
          Deeper-World
        </nuxt-link>
      </div>
      <div></div>
    </div>
  </nav>
</template>

<script>
export default {
  data: () => ({
    toggleMenu: true
  })
}
</script>
