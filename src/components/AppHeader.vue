<template>
  <header>
    <h1>Website {{host}}</h1>
  </header>
</template>

<script setup lang="ts">
let currentUrl: string | number = location.toString();

let host: string | number = location.host;
</script>

<style scoped>
  header {
    display: flex;
    border-bottom: 1px solid #ccc;
    padding: .1rem;
    align-items: center;
    justify-content: center;
  }
</style>
