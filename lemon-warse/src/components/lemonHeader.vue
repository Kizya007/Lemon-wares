<template>
  <header>
    <div class="logo">
      <img src="../assets/img/logo.png" alt="" />
    </div>
    <div class="menu">Menu</div>
    <nav class="navigation">
      <li class="navigation-item"><a href="">Our Services</a></li>
      <li class="navigation-item"><a href="">About</a></li>
      <li class="navigation-item"><a href=""> Blog&News</a></li>
      <li class="navigation-item"><a href="">Contact</a></li>
    </nav>
    <div class="info">
      <button class="info-btn">Account</button>
      <div class="line"></div>
      <PhoneIcon />
      <p class="info-number">+2349067322844</p>
    </div>
  </header>
</template>

<script>
import PhoneIcon from "../assets/icon/PhoneIcon.vue";
export default {
  components: {
    PhoneIcon,
  },
};
</script>

<style lang="scss">
@import "../assets/Header.scss";
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&family=Poppins:wght@400;500;600;700&display=swap");
</style>
