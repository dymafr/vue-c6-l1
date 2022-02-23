<template>
  <button @click="toggle = !toggle">Toggle</button>
  <h1 v-if="toggle">Hello le monde !</h1>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const toggle = ref(true);
</script>

<style scoped lang="scss"></style>
