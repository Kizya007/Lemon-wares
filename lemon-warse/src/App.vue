<template>
  <BannerInfo/>
</template>

<script>
import BannerInfo from "./components/BannerInfo.vue"

export default {
  name: 'App',
  components: {
    BannerInfo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
