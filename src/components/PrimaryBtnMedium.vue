<script setup>
const { btnText } = defineProps({
  btnText: String,
})
</script>

<template>
  <button class="primary-btn-medium btn-primary-base">{{ btnText }}</button>
</template>

<style scoped>
.primary-btn-medium {
  cursor: pointer;
  padding: 10px 20px;
  border-radius: 6px;
  border: none;
  color: var(--White);
  background-color: var(--Primary);
  line-height: 20px;
  font-size: 14px;
  font-weight: 500;

  &:active {
    background-color: var(--green-Shade2);
  }
}
</style>
