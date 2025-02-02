<script setup>
const { imgPath, heading, btnText } = defineProps({
  imgPath: String,
  heading: String,
  btnText: String,
})
</script>

<template>
  <div class="community-card">
    <img :src="imgPath" alt="" />
    <div class="card-content u-shadow-m">
      <h4 class="heading-quaternary u-text-center">{{ heading }}</h4>
      <button class="readmore-btn">{{ btnText }}</button>
    </div>
  </div>
</template>

<style scoped>
.community-card {
  position: relative;
  width: 368px;
  height: 286px;
}
.card-content {
  position: absolute;
  top: 190px;
  left: 25.5px;
  z-index: 1;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 16px;
  background-color: var(--Silver);
  padding: 16px;
  width: 317px;
  height: 176px;
  border-radius: 8px;
}
.readmore-btn {
    cursor: pointer;
  color: var(--Primary);
  background-color: transparent;
  border: none;
  line-height: 28px;
  font-size: 20px;
  font-weight: 600;
}
.readmore-btn::after {
  content: '→';
  margin-left: 8px;
}
</style>
