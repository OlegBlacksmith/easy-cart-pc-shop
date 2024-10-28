<script setup lang="ts">
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
public class Product { public string PublicId { get; set; } public string Name {
get; set; } public int Stock { get; set; } // Поле для хранения динамических
характеристик товара public string DetailsJson { get; set; } public int
CategoryId { get; set; } public Category Category { get; set; } public
ManufacturerId { get; set; } }
