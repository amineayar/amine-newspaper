<script setup>
import Article from './components/Article.vue'
</script>

<template>
  <h1>Digital Articles</h1>
  <div class="main-container">
    <Article />
    <Article />
    <Article />
    <Article />
    <Article />
    <Article />
    <Article />
    <Article />
    <Article />
    <Article />
  </div>
</template>

<style scoped>
.main-container {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}
</style>