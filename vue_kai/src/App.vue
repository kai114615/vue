<script setup>
import FirstComponment from './components/FirstComponment.vue';
import { ref } from 'vue';
const message = ref("kai")

</script>

<template>
  <h2>kai</h2>
  <hr>
  <FirstComponment></FirstComponment>

</template>

<style scoped>
.h2{color: aqua;
}
</style>
