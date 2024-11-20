<script setup>
import productos from '../assets/productos.json' // Revisa que la ruta sea correcta
</script>

<template>
  <ul>
    <li v-for="product in productos" :key="product.id">
      <RouterLink :to="'/productDetail/' + product.id">{{ product.name }}</RouterLink>
    </li>
  </ul>
</template>

<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin-bottom: 10px;
}
</style>
