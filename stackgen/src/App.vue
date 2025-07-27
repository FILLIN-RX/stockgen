<script setup>

import { RouterView } from 'vue-router'
import Navbar from './components/NavBar.vue'

</script>

<template>
  <Navbar />
  <main class="bg-white">
    <RouterView />
  </main>
</template>

<style scoped>

</style>
