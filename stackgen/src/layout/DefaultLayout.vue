<template>
  <div class="min-h-screen flex">
    <!-- Sidebar -->
    <aside class="w-64 bg-gray-800 text-white p-4">
    <NavBar/>
    </aside>

    <!-- Main content -->
    <main class="flex-1 scroll-m-0 p-6 bg-gray-100">
      <SecondNav />
      <router-view />
    </main>
  </div>
</template>
<script setup>
import NavBar from '../components/NavBar.vue'
import SecondNav from '../components/SecondNav.vue'
</script>
