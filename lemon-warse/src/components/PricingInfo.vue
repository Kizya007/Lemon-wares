<template>
  <div class="pricing">
    <p class="pricing-title">
      Ready to get started with <br />
      Lemon Wares?
    </p>
    <p class="pricing-subtitle">Choose the package that suits you</p>
    <div class="subscribe">
      <span class="subscribe-left">Monthly</span>
      <div class="switch">
        <div class="switch-elipse"></div>
      </div>
      <span class="subscribe-right">Yearly</span>
      <span class="subscribe-discount">20% discount</span>
    </div>
    <div class="subscribe-variants">
      <div class="variants-left">
        <p class="variants-left__text">Basic</p>
        <div class="variants-left__line"></div>
      </div>
      <div class="variants-right">
        <p class="variants-right__text">Premium</p>
        <div class="variants-right__line"></div>
      </div>
    </div>
    <div class="cards">
      <div class="card">
        <p class="card-title">Starter</p>
        <p class="card-subtitle">
          with all your customers via all <br />
          conversation channels in one central <br />
          dashboard.
        </p>
        <p class="card-price">$2.80</p>
        <p class="card-duration">Per month</p>
        <button class="card-btn">Choose this Plan</button>
        <ul class="card-list">
          <li class="card-list__item"><CheckIcon />2GB SSD</li>
          <li class="card-list__item"><CheckIcon />10GB Bandwidth</li>
          <li class="card-list__item"><CheckIcon />15 Email Accounts</li>
          <li class="card-list__item"><CheckIcon />Unlimited Database</li>
          <li class="card-list__item"><CheckIcon />4 Subdomains</li>
          <li class="card-list__item"><CheckIcon />1 Parked Domain</li>
          <li class="card-list__item"><CheckIcon />2 Websites</li>
          <li class="card-list__item"><CheckIcon />Free SSL</li>
          <li class="card-list__item"><CheckIcon />Softaculous</li>
        </ul>
      </div>
      <div class="card">
        <p class="card-title">Standart</p>
        <p class="card-subtitle">
          with all your customers via all <br />
          conversation channels in one central <br />
          dashboard.
        </p>
        <p class="card-price">$4.20</p>
        <p class="card-duration">Per month</p>
        <button class="card-btn">Choose this Plan</button>
        <ul class="card-list">
          <li class="card-list__item"><CheckIcon />2GB SSD</li>
          <li class="card-list__item"><CheckIcon />10GB Bandwidth</li>
          <li class="card-list__item"><CheckIcon />15 Email Accounts</li>
          <li class="card-list__item"><CheckIcon />Unlimited Database</li>
          <li class="card-list__item"><CheckIcon />4 Subdomains</li>
          <li class="card-list__item"><CheckIcon />1 Parked Domain</li>
          <li class="card-list__item"><CheckIcon />2 Websites</li>
          <li class="card-list__item"><CheckIcon />Free SSL</li>
          <li class="card-list__item"><CheckIcon />Softaculous</li>
        </ul>
      </div>
      <div class="card">
        <p class="card-title">Suprem</p>
        <p class="card-subtitle">
          with all your customers via all <br />
          conversation channels in one central <br />
          dashboard.
        </p>
        <p class="card-price">$7.00</p>
        <p class="card-duration">Per month</p>
        <button class="card-btn">Choose this Plan</button>
        <ul class="card-list">
          <li class="card-list__item"><CheckIcon />2GB SSD</li>
          <li class="card-list__item"><CheckIcon />10GB Bandwidth</li>
          <li class="card-list__item"><CheckIcon />15 Email Accounts</li>
          <li class="card-list__item"><CheckIcon />Unlimited Database</li>
          <li class="card-list__item"><CheckIcon />4 Subdomains</li>
          <li class="card-list__item"><CheckIcon />1 Parked Domain</li>
          <li class="card-list__item"><CheckIcon />2 Websites</li>
          <li class="card-list__item"><CheckIcon />Free SSL</li>
          <li class="card-list__item"><CheckIcon />Softaculous</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import CheckIcon from "../assets/icon/CheckIcon";

export default {
  components: {
    CheckIcon,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/Pricing.scss";
</style>
