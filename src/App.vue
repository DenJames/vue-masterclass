<script setup lang="ts">
</script>

<template>
<main>
  <RouterView />

  <nav class="navbar">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/projects">All projects</RouterLink>
  </nav>
</main>
</template>

<style scoped>
.navbar {
  display: flex;
  gap: 10px;
  padding: 1rem;
  background-color: #f3f3f3;
}
</style>