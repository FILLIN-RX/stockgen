<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/NavBar.vue'
</script>

<template>
  <Navbar />
  <div class="h-screen">
    <RouterView />
  </div>
</template>

<style scoped></style>
