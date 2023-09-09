<script setup>
const current = new Date().toLocaleString("en-us", {
  day: "numeric",
  month: "short",
  year: "numeric",
});
</script>

<template>
  <div class="intro">
    <p class="date">Today is {{ current }}</p>
  </div>
</template>

<style lang="scss" scoped>
.intro {
  display: flex;
  padding: 20px 16px;
  flex-direction: column;
  align-items: center;

  .date {
    color: white;
  }
}
</style>
