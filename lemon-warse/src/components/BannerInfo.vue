<template>
  <div class="banner">
    <p class="banner-title">We're here to make your <br> website awesome.</p>
    <button class="banner-btn"><WhatsupIcon /> Get in touch with us</button>
  </div>
</template>

<script>
import WhatsupIcon from "@/assets/icon/WhatsupIcon.vue";

export default {
  components: {
    WhatsupIcon,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/Banner.scss";
</style>
