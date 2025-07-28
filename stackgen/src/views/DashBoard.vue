<template>
  <h1 class="text-2xl font-bold">Tableau de bord</h1>
  <GrapHs/>
  <div class="grid grid-cols-3">
    
      <BestSales/>

      <StockProduct/>

  </div>
</template>
<script setup>
import GrapHs from '@/components/GrapHs.vue';
import BestSales from '@/components/BestSales.vue'
import StockProduct from '@/components/StockProduct.vue';
</script>
