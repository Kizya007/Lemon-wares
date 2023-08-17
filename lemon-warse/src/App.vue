<template>
  <div>
    <lemonHeader />
    <InformationPage />
    <AboutInfo />
    <PricingInfo />
    <ReviewsStories />
    <BannerInfo />
  </div>
</template>

<script>
import lemonHeader from "./components/lemonHeader.vue";
import AboutInfo from "./components/AboutInfo.vue";
import InformationPage from "./components/InformationPage.vue";
import PricingInfo from "./components/PricingInfo.vue";
import ReviewsStories from "./components/ReviewsStories.vue";
import BannerInfo from "./components/BannerInfo.vue";

export default {
  name: "App",
  components: {
    lemonHeader,
    AboutInfo,
    InformationPage,
    PricingInfo,
    ReviewsStories,
    BannerInfo,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&family=Poppins:wght@400;500;600;700&display=swap");
@import "./assets/global.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
