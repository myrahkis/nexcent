<script setup>
import Logo from '@/ui/Logo.vue'
</script>

<template>
  <header class="header">
    <Logo />
    <ul class="heading-names">
      <li>Home</li>
      <li>Services</li>
      <li>Feature</li>
      <li>Product</li>
      <li>Testimonial</li>
      <li>FAQ</li>
    </ul>
    <div class="btns">
      <button class="login-btn">Login</button>
      <button class="signup-btn">Sign up</button>
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

  li {
    cursor: pointer;
  }
}
.btns {
  display: flex;
  gap: 14px;
}
.login-btn {
  padding: 10px 20px;
  color: var(--Primary);
  background-color: var(--Silver);
  border: none;
  line-height: 20px;
  font-size: 14px;
  font-weight: 500;
}
.signup-btn {
  padding: 10px 20px;
  border-radius: 6px;
  border: none;
  color: var(--White);
  background-color: var(--Primary);
  line-height: 20px;
  font-size: 14px;
  font-weight: 500;
}
</style>
