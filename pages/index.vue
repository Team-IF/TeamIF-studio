<template>
  <div class="text-center mt-48 text-white">
    <div class="blending text-6xl font-black text-white">
      TeamIF Game Studio
    </div>
    <mainBtn />
  </div>
</template>

<script scoped>
import Logo from '~/components/Logo.vue'
import mainBtn from '~/components/MainBtn'

export default {
  layout: 'home',
  components: {
    // eslint-disable-next-line vue/no-unused-components
    Logo,
    mainBtn
  }
}
</script>

<style>
.blending {
  mix-blend-mode: overlay;
}
</style>
