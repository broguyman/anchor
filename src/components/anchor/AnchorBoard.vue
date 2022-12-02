<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="board"></div>
</template>

<style scoped>
.board {
  background-color: #000;
  width: 100%;
  height: 100%;
}
</style>
