<script setup>
import { ref } from 'vue';
const message = ref("響應式API")
</script>

<template>
    <h2>第二個組件</h2>
    <input type="text" value="" v-model="message">
    <p>{{ message }}</p>
    <hr>
</template>

<style scoped>
h2{
    color: aqua;
}
</style>