<script setup>
const { heading, links } = defineProps({
  heading: String,
  links: Array,
})
</script>

<template>
  <div class="company">
    <h4 class="links-heading">{{ heading }}</h4>
    <ul class="links-list">
      <li v-for="link in links" :key="link">{{ link }}</li>
    </ul>
  </div>
</template>

<style scoped>
.links-list {
  display: flex;
  flex-direction: column;
  gap: 12px;
  margin-top: 24px;
  color: var(--White);
  list-style: none;

  li {
    cursor: pointer;
    font-weight: 400;
    line-height: 20px;
    font-size: 14px;
  }
}
.links-heading {
  color: var(--White);
}
</style>
