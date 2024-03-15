<script setup>
import { ref } from 'vue'
const count = ref(1);

const increment = () => {
    count.value++;
}
</script>

<template>
    <div>
      <button @click="increment">
          Count:
          <strong>{{ count }}</strong>
      </button>
    </div>
  </template>
