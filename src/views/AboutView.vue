<script setup></script>

<template>
  <main>
    <p class="header-msg">
      <img src="../assets/aki.png" alt="aki" />
      <span>Just do your own business.</span>
    </p>
  </main>
</template>

<style lang="scss" scoped>
main {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  width: 100%;
  margin: 0 auto;
  padding: 40px 16px;

  .header-msg {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 5px;
    margin-bottom: 16px;
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    color: coral;

    img {
      max-width: 100px;
    }
  }
}
</style>
