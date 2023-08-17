<template>
  <div>
    <FooterInfo />
  </div>
</template>

<script>
import FooterInfo from "./components/FooterInfo.vue";

export default {
  name: "App",
  components: {
    FooterInfo,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Poppins:wght@300;400;500;600;700&display=swap");
@import "./assets/global.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
