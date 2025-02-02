<script setup></script>

<template>
  <section class="customers-section">
    <img src="/img/image9.png" alt="" class="customers-img" />
    <div class="customers-block">
      <div class="content">
        <p class="customers-text u-mb-m">
          Maecenas dignissim justo eget nulla rutrum molestie. Maecenas lobortis sem dui, vel rutrum
          risus tincidunt ullamcorper. Proin eu enim metus. Vivamus sed libero ornare, tristique
          quam in, gravida enim. Nullam ut molestie arcu, at hendrerit elit. Morbi laoreet elit at
          ligula molestie, nec molestie mi blandit. Suspendisse cursus tellus sed augue ultrices,
          quis tristique nulla sodales. Suspendisse eget lorem eu turpis vestibulum pretium.
          Suspendisse potenti. Quisque malesuada enim sapien, vitae placerat ante feugiat eget.
          Quisque vulputate odio neque, eget efficitur libero condimentum id. Curabitur id nibh id
          sem dignissim finibus ac sit amet magna.
        </p>
        <h4><span class="green-empasis">Tim Smith</span></h4>
        <p class="customers-association u-mt-s u-mb-l">British Dragon Boat Racing Association</p>
        <div class="customers-logos">
          <img src="/img/logos/Logo-1.png" alt="" />
          <img src="/img/logos/Logo-2.png" alt="" />
          <img src="/img/logos/Logo-3.png" alt="" />
          <img src="/img/logos/Logo-4.png" alt="" />
          <img src="/img/logos/Logo-5.png" alt="" />
          <img src="/img/logos/Logo-6.png" alt="" />
          <button class="customers-btn">Meet all customers</button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.customers-section {
  display: flex;
  align-items: center;
  background-color: var(--Silver);
  height: 390px;
  gap: 78px;
  padding: 32px 144px;
  margin-top: 48px;
}
.customers-img {
  width: 326px;
  height: 326px;
}
.customers-text {
  color: var(--Grey);
  line-height: 24px;
  font-size: 16px;
  font-weight: 500;
}
.customers-association {
  color: var(--Grey);
  font-weight: 400;
  line-height: 24px;
  font-size: 16px;
}
.customers-logos {
  display: flex;
  gap: 41px;
}
.customers-btn {
  cursor: pointer;
  padding: 8px;
  border: none;
  background-color: transparent;
  color: var(--Primary);
  font-weight: 600;
  line-height: 28px;
  font-size: 20px;
}
.customers-btn::after {
  content: '→';
  margin-left: 8px;
}
</style>
