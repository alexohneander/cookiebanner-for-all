<template>
  <div id="cookiebanner">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Banner/>
  </div>
</template>

<script>
import Banner from './components/Banner.vue'

export default {
  name: 'cookiebanner',
  components: {
    Banner
  }
}
</script>

<style>
#cookiebanner {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
