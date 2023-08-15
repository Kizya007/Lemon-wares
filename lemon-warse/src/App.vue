<template>
  <div>
    <ReviewsStories />
  </div>
</template>

<script>
import ReviewsStories from "./components/ReviewsStories.vue";

export default {
  name: "App",
  components: {
    ReviewsStories,
  },
};
</script>

<style>
@import "./assets/global.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
