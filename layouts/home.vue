<template>
  <div id="mainBG">
    <link
      href="https://fonts.googleapis.com/css?family=Lato|Roboto:400,900"
      rel="stylesheet"
      type="text/css"
    />
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
  font-family: 'Roboto', sans-serif;
  height: 100vh;
}
#mainBG {
  width: 100%;
  height: 100vh;
  position: relative;
  overflow: hidden;
  background: linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)),
    #ffffff
      url('https://cdn.discordapp.com/attachments/704599887416655994/714753465292685352/jake-blucker-z6F6UBQZyv0-unsplash_1.jpg')
      50% 50% no-repeat;
  background-blend-mode: exclusion;
  background-blend-mode: luminosity;
  background-size: cover;
}
</style>
