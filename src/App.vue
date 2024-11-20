<script setup></script>

<template>
  <!-- Routerlink -->
  <router-link to="/about">About</router-link>
  <!-- Navigation bar -->
  <nav>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/contact">Contact</router-link></li>
      <li><router-link to="/products">Productes</router-link></li>
    </ul>
  </nav>

  <!-- Dynamic content -->
  <div class="container"></div>
</template>

<style scoped></style>
