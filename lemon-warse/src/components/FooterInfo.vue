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
    <div class="right-block">
      <div class="lists">
        <h3 class="lists-heading">Service</h3>
        <ul class="list">
          <li class="list-item"><a href="">Domain</a></li>
          <li class="list-item"><a href="">Hosting</a></li>
          <li class="list-item"><a href="">Cloud Hosting</a></li>
          <li class="list-item"><a href="">Private Hosting</a></li>
        </ul>
      </div>
      <div class="lists">
        <h3 class="lists-heading">Hosting</h3>
        <ul class="list">
          <li class="list-item"><a href="">Cheap Hosting</a></li>
          <li class="list-item"><a href="">Hosting Wordpress</a></li>
          <li class="list-item"><a href="">Email Hosting</a></li>
          <li class="list-item"><a href="">Hosting Unlimited</a></li>
        </ul>
      </div>
      <div class="lists">
        <h3 class="lists-heading">Company</h3>
        <ul class="list">
          <li class="list-item"><a href="">About</a></li>
          <li class="list-item"><a href="">Career</a></li>
          <li class="list-item"><a href="">Contact Us</a></li>
        </ul>
      </div>
      <div class="lists">
        <h3 class="lists-heading">Help</h3>
        <ul class="list">
          <li class="list-item"><a href="">FAQ</a></li>
          <li class="list-item"><a href="">Help support</a></li>
        </ul>
      </div>
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
