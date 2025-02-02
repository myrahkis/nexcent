<script setup></script>

<template>
  <section class="clients-section">
    <h2 class="heading-secondary u-mb-s">Our Clients</h2>
    <p class="text u-mb-m">We have been working with some Fortune 500+ clients</p>
    <div class="clints-logos">
      <img src="/img/logos/Logo.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-1.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-2.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-3.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-4.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-5.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-6.png" alt="" class="cl-logo" />
    </div>
  </section>
</template>

<style scoped>
.clients-section {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 190px;
  margin: 40px 0;
}
.clints-logos {
  display: flex;
  max-width: 1152px;
  width: 1152px;
  height: 98px;
  gap: 40px;
  justify-content: space-around;
  align-items: center;
  margin-top: 16px;
}
.cl-logo {
  width: 48px;
  height: 48px;
}
</style>
