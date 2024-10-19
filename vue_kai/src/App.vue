<script setup>
import FirstComponment from './components/FirstComponment.vue';
import SecondComponment from './components/SecondComponment.vue';
import { ref } from 'vue';
const message = ref("kai")

</script>

<template>
  <h2>kai</h2>
  <hr>
  <FirstComponment></FirstComponment>
  <!-- <first-componment></first-componment> -->

  <SecondComponment></SecondComponment>
</template>

<style scoped>
</style>
