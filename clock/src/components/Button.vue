<script setup>
</script>

<template>
  <button class="button">
    <slot></slot>
  </button>
</template>

<style scoped>
.button {
  border: transparent;
  border-radius: 100px;
  text-align: center;
  background: var(--color-btn);
  font-size: 24px;
  height: 68px;
  line-height: 68px;
  min-width: 315px;
  color: var(--color-primary-inverted);
  cursor: pointer;
}
.button:hover {
  background: var(--color-btn-hover);
}
</style>