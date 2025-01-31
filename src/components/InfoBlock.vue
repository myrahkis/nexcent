<script setup>
const { imgPath, heading, paragraph, btnText } = defineProps({
  imgPath: String,
  heading: String,
  paragraph: String,
  btnText: String,
})
</script>

<template>
  <section class="section">
    <img :src="imgPath" alt="" class="illustration" />
    <div class="info-block">
      <h2 class="heading u-mb-m">{{ heading }}</h2>
      <p class="text">
        {{ paragraph }}
      </p>
      <button class="learn-more-btn">{{ btnText }}</button>
    </div>
  </section>
</template>

<style scoped>
.section {
  display: flex;
  align-items: center;
  justify-content: space-around;
  background-color: var(--White);
  max-height: 100%;
  height: 433.4px;
  padding: 0 144px;
}
.info-block {
  max-width: 657px;
}
.heading {
  color: var(--D_Grey);
}
.green-empasis {
  color: var(--Primary);
}
.text {
  color: var(--Grey);
  line-height: 20px;
  font-size: 14px;
}
.learn-more-btn {
  background-color: var(--Primary);
  color: var(--White);
  border: none;
  border-radius: 4px;
  padding: 14px 32px;
  margin-top: 32px;
  font-weight: 500;
  line-height: 24px;
  font-size: 16px;
}
.illustration {
  height: 407px;
  width: 441.5px;
}
</style>
