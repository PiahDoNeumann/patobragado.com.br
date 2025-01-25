<template>
  <footer>
    <p>Copyright &copy; {{ year }} </p>
  </footer>
</template>

<script setup lang="ts">

let year = new Date().getFullYear();
</script>
