<template>
  <div class="min-h-screen flex">
    <!-- Sidebar -->
    <aside class="w-64 bg-gray-800 text-white p-4">
      <nav>
        <ul>
          <li class="mb-4"><router-link to="/" class="hover:underline">Dashboard</router-link></li>
          <li><router-link to="/produits" class="hover:underline">Produits</router-link></li>
        </ul>
      </nav>
    </aside>

    <!-- Main content -->
    <main class="flex-1 p-6 bg-gray-100">
      <router-view />
    </main>
  </div>
</template>
