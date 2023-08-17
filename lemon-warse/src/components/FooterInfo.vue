<template>
  <div class="footer">
    <div class="left-block">
      <div class="left-block__img">
        <img src="../assets/img/WhiteLogo.png" alt="" />
      </div>
      <p class="left-block__text">
        Lorem ipsum dolor sit amet, <br />
        consectetur adipiscing elit ut aliquam, <br />
        purus sit amet luctus venenatis, lectus <br />
        magna fringilla urna, porttitor rhoncus <br />
        dolor purus non enim praesent elem
      </p>
      <p class="left-block__copyright">
        Built by Jeremiah with <HeartsIcon /> love in Lagos. Copyright 2021
      </p>
    </div>
    <div class="footer-lists">
      <ul class="footer-list">
        <li class="footer-list__title"><a href="">Service</a></li>
        <li class="footer-list__item"><a href="">Domain</a></li>
        <li class="footer-list__item"><a href="">Hosting</a></li>
        <li class="footer-list__item"><a href="">Cloud Hosting</a></li>
        <li class="footer-list__item"><a href="">Private Hosting</a></li>
      </ul>
      <ul class="footer-list">
        <li class="footer-list__title"><a href="">Hosting</a></li>
        <li class="footer-list__item"><a href="">Cheap Hosting</a></li>
        <li class="footer-list__item"><a href="">Hosting Wordpress</a></li>
        <li class="footer-list__item"><a href="">Email Hosting</a></li>
        <li class="footer-list__item"><a href="">Hosting Unlimited</a></li>
      </ul>
      <ul class="footer-list">
        
        <li class="footer-list__title"><a href="">Company</a></li>
        <li class="footer-list__item"><a href="">About</a></li>
        <li class="footer-list__item"><a href="">Career</a></li>
        <li class="footer-list__item"><a href="">Contact Us</a></li>
      </ul>
      <ul class="footer-list">
        <li class="footer-list__title"><a href="">Help</a></li>
        <li class="footer-list__item"><a href="">FAQ</a></li>
        <li class="footer-list__item"><a href="">Help support</a></li>
        
      </ul>
    </div>
  </div>
</template>

<script>
import HeartsIcon from "../assets/icon/HeartsIcon.vue";

export default {
  components: {
    HeartsIcon,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/Footer.scss";
</style>
