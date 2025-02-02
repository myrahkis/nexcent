<script setup>
import Logo from '@/ui/Logo.vue'
import PrimaryBtnMedium from '@/components/PrimaryBtnMedium.vue'
import TertiaryBtnMedium from '@/components/TertiaryBtnMedium.vue'
</script>

<template>
  <header class="header">
    <Logo />
    <ul class="heading-names">
      <li class="link">Home</li>
      <li class="link">Services</li>
      <li class="link">Feature</li>
      <li class="link">Product</li>
      <li class="link">Testimonial</li>
      <li class="link">FAQ</li>
    </ul>
    <div class="btns">
      <TertiaryBtnMedium btnText="Login" />
      <PrimaryBtnMedium btnText="Sign up" />
    </div>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  width: 100%;
  background-color: var(--Silver);
  justify-content: space-around;
  align-items: center;
  padding: 15px;

  .logo {
    cursor: pointer;
  }
}
.heading-names {
  display: flex;
  list-style: none;
  line-height: 24px;
  font-size: 16px;
  gap: 45px;
  font-weight: 400;
}
.btns {
  display: flex;
  gap: 14px;
}
</style>
