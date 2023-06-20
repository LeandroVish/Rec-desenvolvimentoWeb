<script setup>
import ItemMercado from '@/components/ItemMoveis.vue'
import MeuCarrinho from '@/components/MeuCarrinho.vue'
</script>

<template>
  <h1>LM Moveis</h1>
  <div class="container">
    <item-mercado />
    <meu-carrinho />
  </div>
</template>

<style scoped>
.container {
  display: grid;
  grid-template-columns: 4fr 2fr;
}
</style>
