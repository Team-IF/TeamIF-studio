<template>
  <div id="mainBG">
    <Navbar />
    <nuxt />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  height: 100vh;
}
#mainBG {
  background-image: url('https://cdn.discordapp.com/attachments/704599887416655994/714753465292685352/jake-blucker-z6F6UBQZyv0-unsplash_1.jpg');
  background-size: cover;
  height: 100vh;
}
</style>
