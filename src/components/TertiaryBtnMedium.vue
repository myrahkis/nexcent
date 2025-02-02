<script setup>
const { btnText } = defineProps({ btnText: String })
</script>

<template>
  <button class="tertiary-btn-medium btn-tertiary-base">{{ btnText }}</button>
</template>

<style scoped>
.tertiary-btn-medium {
  cursor: pointer;
  padding: 10px 20px;
  color: var(--Primary);
  background-color: var(--Silver);
  border: none;
  line-height: 20px;
  font-size: 14px;
  font-weight: 500;

  &:hover {
    background-color: var(--Silver);
  }
  &:active {
    background-color: #e8f5e9;
    color: var(--Primary);
  }
}
</style>
