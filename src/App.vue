<script setup>
import { ref } from "vue";
const sliderValue = ref(50);
</script>
<template>
  <input v-model="sliderValue" type="range" min="0" max="100" class="slider" />
  <br />
  <input v-model="sliderValue" type="number" />
</template>