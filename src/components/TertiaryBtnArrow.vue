<script setup>
const { btnText } = defineProps({
  btnText: String,
})
</script>

<template>
  <button class="tertiary-btn btn-tertiary-base">{{ btnText }}</button>
</template>

<style>
.tertiary-btn {
  cursor: pointer;
  color: var(--Primary);
  background-color: transparent;
  border: none;
  line-height: 28px;
  font-size: 20px;
  font-weight: 600;
  padding: 8px 8px;
}
.tertiary-btn::after {
  content: '→';
  margin-left: 8px;
}
</style>
