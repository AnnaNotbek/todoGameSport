<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
    </nav>
    <div>TEST</div>
  </header>

  <RouterView />
</template>

<style scoped></style>
