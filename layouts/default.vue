<template>
  <div>
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
  background-color: #fafafa;
}
</style>
