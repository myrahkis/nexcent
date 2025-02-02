<script setup>
import PrimaryBtn from './PrimaryBtn.vue'
</script>

<template>
  <section class="hero-section">
    <div class="info-block">
      <h1 class="heading u-mb-m">
        Lessons and insights <span class="green-empasis">from 8 years</span>
      </h1>
      <p class="text">Where to grow your business as a photographer: site or social media?</p>
      <PrimaryBtn btnText="Register" />
    </div>
    <img src="/img/Illustration.png" alt="" class="illustration" />
  </section>
</template>

<style scoped>
.hero-section {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: var(--Silver);
  max-height: 100%;
  height: 599px;
  gap: 104px;
}
.info-block {
  max-width: 657px;
}
.heading {
  color: var(--D_Grey);
}
.text {
  color: var(--Grey);
  line-height: 24px;
  font-size: 16px;
}
.illustration {
  height: 407px;
  width: 391px;
}
</style>
