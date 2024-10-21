<script setup lang="ts">
import { ref } from 'vue';

const isLogin = ref(false);
const getName = ()=> 'kai';
</script>

<template>
    <div>
        <h2>第三個組件 {{ getName()}} </h2>
        <p>{{isLogin ? "yes" : "no"}}</p>
        <hr>
    </div>
</template>

<style lang="css" scoped>

</style>