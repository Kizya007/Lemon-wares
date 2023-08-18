<template>
  <div>
    <lemonHeader />
    <InformationPage />
    <AboutInfo />
    <PricingInfo />
    <ReviewsStories />
    <BannerInfo />
    <FooterInfo />
  </div>
</template>

<script>
import lemonHeader from "./components/lemonHeader.vue";
import InformationPage from "./components/InformationPage.vue";
import AboutInfo from "./components/AboutInfo.vue";
import PricingInfo from "./components/PricingInfo.vue";
import ReviewsStories from "./components/ReviewsStories.vue";
import BannerInfo from "./components/BannerInfo.vue";
import FooterInfo from "./components/FooterInfo.vue";

export default {
  name: "App",
  components: {
    lemonHeader,
    InformationPage,
    AboutInfo,
    PricingInfo,
    ReviewsStories,
    BannerInfo,
    FooterInfo,
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
  color: #2c3e50;
  margin-top: 20px;
}
</style>
