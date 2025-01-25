<template>
  <header>
    <section class="w-full mb-8">
      <h1 class="text-2xl font-semibold text-gray-800">
        Website {{host}}
      </h1>
    </section>
  </header>
</template>

<script setup lang="ts">
let currentUrl: string | number = location.toString();

let host: string | number = location.host;
</script>

