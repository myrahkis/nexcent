<script setup>
const { imgPath, stat, name } = defineProps({
  imgPath: String,
  stat: String,
  name: String,
})

const fullImgPath = `${import.meta.env.BASE_URL}${imgPath}`
</script>

<template>
  <div class="stat-group">
    <img :src="fullImgPath" alt="" class="stat-img" />
    <div class="stats">
      <h3 class="heading-tertiary">{{ stat }}</h3>
      <p class="body2">{{ name }}</p>
    </div>
  </div>
</template>

<style scoped>
.stat-group {
  display: flex;
  width: 255px;
  gap: 16px;
}
.stat-img {
  width: 48px;
  height: 48px;
}
.body2 {
  line-height: 24px;
  font-size: 16px;
  font-weight: 400;
  color: var(--Grey);
}
</style>
