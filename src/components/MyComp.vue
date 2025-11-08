<script setup>
import { ref } from "vue";

const myVar = ref(0);
</script>

<template>
  <h2>{{ myVar }}</h2>
  <button @click="myVar++">pushme</button>
</template>
