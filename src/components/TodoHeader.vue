<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header>
    <nav class="container">
      <div class="branding">
        <h1>PoPo</h1>
        <img src="../assets/logo.png" alt="vue logo" />
        <h1>ToDos</h1>
      </div>
      <ul class="nav-routes">
        <router-link to="/" class="link">Home</router-link>
        <router-link to="/about" class="link">About</router-link>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #7a7a7a;
  nav {
    display: flex;
    align-items: center;
    padding: 16px 16px;

    .branding {
      display: flex;
      align-items: center;
      gap: 8px;
      img {
        max-width: 50px;
      }

      h1 {
        font-size: 35px;
      }
    }

    .nav-routes {
      display: flex;
      flex: 1;
      justify-content: flex-end;
      gap: 30px;
      list-style: none;
      font-size: 20px;

      .link {
        text-decoration: none;
        color: inherit;
      }

      .link.active {
        font-weight: bold;
      }
    }
  }
}
</style>
