<script setup>
import ButtonCount from './components/ButtonCount.vue';
import FirstComponment from './components/FirstComponment.vue';
import SecondComponment from './components/SecondComponment.vue';
import ThirdComponment from './components/ThirdComponment.vue';
import { ref } from 'vue';
const message = ref("kai")

</script>

<template>
  <h2>kai</h2>
  <hr>
  <FirstComponment></FirstComponment>
  <!-- <first-componment></first-componment> -->

  <SecondComponment></SecondComponment>
  <ThirdComponment></ThirdComponment>
  <ButtonCount></ButtonCount>
</template>

<style scoped>
</style>
