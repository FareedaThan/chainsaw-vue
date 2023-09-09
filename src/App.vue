<script setup>
import TodoHeader from "./components/TodoHeader.vue";
import { RouterView } from "vue-router";
</script>

<template>
  <TodoHeader />
  <RouterView />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Comic+Neue:wght@400;700&display=swap");

* {
  font-family: "Comic Neue", cursive;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: black;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
