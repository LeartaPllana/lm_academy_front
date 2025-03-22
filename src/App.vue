<template>
  <div>
    <p>{{ message }}</p>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const message = ref('Learta')

setTimeout(() => {
  message.value = 'Perfundoj kursi per sot!'
}, 5000)
</script>

<style>
p {
  color: red;
}
</style>
