<script setup></script>

<template>
  <section class="get-demo-section">
    <h1 class="heading u-text-center">
      Pellentesque suscipit <br />
      fringilla libero eu.
    </h1>
    <button class="demo-btn">Get a Demo</button>
  </section>
</template>

<style scoped>
.get-demo-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 300px;
  background-color: var(--Silver);
  color: var(--Black);
  gap: 32px;
}
.heading {
  width: 887px;
}
.demo-btn {
  cursor: pointer;
  border: none;
  border-radius: 4px;
  background-color: var(--Primary);
  padding: 14px 32px;
  color: var(--White);
}
.demo-btn::after {
  content: '→';
  margin-left: 8px;
}
</style>
