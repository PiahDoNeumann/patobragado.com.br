<template>
  <header>
    <h1>Website {{host}}</h1>
  </header>
</template>

<script>
export default {
  name: 'Header',

  data () {
      return {
        currentUrl: location.toString(),
        host: location.host
      }
    }
}
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