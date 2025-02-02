<script setup>
const { btnText } = defineProps({ btnText: String })
</script>

<template>
  <button class="primary-btn btn-primary-base">{{ btnText }}</button>
</template>

<style scoped>
.primary-btn {
  cursor: pointer;
  background-color: var(--Primary);
  color: var(--White);
  border: none;
  border-radius: 4px;
  padding: 14px 32px;
  margin-top: 32px;
  font-weight: 500;
  line-height: 24px;
  font-size: 16px;

  &:active {
    background-color: var(--green-Shade2);
  }
}
</style>
