<!-- src/App.vue -->
<template>
  <div id="app">
    <TodoList />
  </div>
</template>

<script setup>
import TodoList from './components/TodoList.vue';
</script>

<style>
/* Tambahkan styling global di sini jika diperlukan */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
}
</style>
