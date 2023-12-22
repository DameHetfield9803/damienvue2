<script setup>
import { ref } from 'vue'
const names = ref([{ name: "Damien", age: 20 }, { name: "En Quan", age: 20 }, { name: "Daniel", age: 21 }, { name: "Firdaus", age: 22 }])
</script>

<template>
  <div class="one">
    <h1>
      <ul>
        <li v-for="n in names">Hello {{ n.name }},
          you are {{ n.age }} years old </li>
      </ul>
    </h1>
  </div>
</template>

<style scoped></style>