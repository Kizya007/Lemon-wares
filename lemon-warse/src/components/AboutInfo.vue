<template>
  <div class="about">
    <div class="up-block">
      <div class="about-description">
        <h2 class="about-description__title">True Cloud Web Hosting</h2>
        <p class="about-description__text">
          True Cloud Web Hosting All of the hosting packages we offer are
          deployed instantly on our SSD powered cloud. We don’t use dedicated
          servers that operate on single pieces of hardware. Our entire
          infrastructure is built to be reliable, secure, and scalable.
        </p>
      </div>
      <ul class="hostings-list">
        <li class="hostings-list__item"><img src="../assets/img/Cpanel.png" alt="" /></li>
        <li class="hostings-list__item"><img src="../assets/img/Imunify.png" alt="" /></li>
        <li class="hostings-list__item"><img src="../assets/img/Litespeed.png" alt="" /></li>
        <li class="hostings-list__item"><img src="../assets/img/Sota.png" alt="" /></li>
        <li class="hostings-list__item"><img src="../assets/img/Wordpress.png" alt="" /></li>
        <li class="hostings-list__item"><img src="../assets/img/Cloudflare.png" alt="" /></li>
      </ul>
    </div>
    <ul class="cards">
      <li class="card">
        <WatchIcon />
        <p class="card-title">99.9% Uptime</p>
        <p class="card-subtitle">
          We Keep Your Web build Online 24x7x365. Downtime not only costs you
          lost visitors but also damages your reputation and search engine
          rankings.
        </p>
      </li>
      <li class="card">
        <WebHostingIcon />
        <p class="card-title">Blazing Fast Web Hosting</p>
        <p class="card-subtitle">
          We Keep Your Web build Online 24x7x365. Downtime not only costs you
          lost visitors but also damages your reputation and search engine
          rankings.
        </p>
      </li>
      <li class="card">
        <CertificateIcon />
        <p class="card-title">Free SSL Certificates</p>
        <p class="card-subtitle">
          We Keep Your Web build Online 24x7x365. Downtime not only costs you
          lost visitors but also damages your reputation and search engine
          rankings.
        </p>
      </li>
      <li class="card">
        <SupportIcon />
        <p class="card-title">24x7 Friendly Support</p>
        <p class="card-subtitle">
          We Keep Your Web build Online 24x7x365. Downtime not only costs you
          lost visitors but also damages your reputation and search engine
          rankings.
        </p>
      </li>
    </ul>
  </div>
</template>

<script>
import WatchIcon from "../assets/icon/WatchIcon.vue";
import WebHostingIcon from "../assets/icon/WebHostingIcon.vue";
import CertificateIcon from "../assets/icon/CertificateIcon.vue";
import SupportIcon from "../assets/icon/SupportIcon.vue";

export default {
  components: {
    WatchIcon,
    WebHostingIcon,
    CertificateIcon,
    SupportIcon,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/AboutInfo.scss"
</style>
