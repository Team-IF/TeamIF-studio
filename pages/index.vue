<template>
  <div class="text-center mt-48 text-white">
    <div class="blending text-6xl font-black text-black">
      TeamIF Game Studio
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  layout: 'index',
  components: {
    // eslint-disable-next-line vue/no-unused-components
    Logo
  }
}
</script>

<style>
.blending {
  mix-blend-mode: overlay;
}
</style>
