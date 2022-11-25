<template>
  <Nav />
  <div class="container">
    <h1>Welcome to Restaurantly</h1>
  </div>
</template>

<script setup lang="ts">
useHead({
  link: [
    {
      rel: "stylesheet",
      href: "https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css",
      crossorigin: ""
    }
  ]
});
</script>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>
