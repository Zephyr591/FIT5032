<script setup>
import JSONLab from './components/JSON.vue'
</script>

<template>
  <div class="app-container">
    <header>
      <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="100" height="100" />
      <h1>FIT5032 Week 2 JSON & Vue Lab</h1>
    </header>

    <main>
      <JSONLab />
    </main>
  </div>
</template>

<style scoped>
.app-container {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

header {
  text-align: center;
  margin-bottom: 30px;
}

.logo {
  display: block;
  margin: 0 auto 10px;
}
</style>