<script setup></script>

<template>
  <button>
    <slot></slot>
  </button>
</template>

<style lang="scss" scoped>
button {
  padding: 8px 16px;
  border: none;
  font-size: 20px;
  font-weight: bold;

  &:hover {
    cursor: pointer;
  }
}
</style>
