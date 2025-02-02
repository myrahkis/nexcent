<script setup>
const { imgPath, heading, text } = defineProps({
  imgPath: String,
  heading: String,
  text: String,
})
</script>

<template>
  <div class="community-card u-shadow-s">
    <img :src="imgPath" alt="" class="card-icon u-mb-m" />
    <h3 class="heading-tertiary u-mb-s u-text-center" v-html="heading"></h3>
    <p class="card-text u-text-center">{{ text }}</p>
  </div>
</template>

<style scoped>
.community-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 299px;
  height: 260px;
  padding: 32px 24px;
  border-radius: 8px;
}
.card-icon {
  width: 65px;
  height: 56px;
}
.card-text {
  color: var(--Grey);
  font-size: 14px;
  line-height: 20px;
  font-weight: 400;
}
</style>
