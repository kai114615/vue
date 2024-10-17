<script setup>
import { ref } from 'vue';

const week = ["日", "一", "二", "三", "四", "五", "六"]
const author = ref({
  books:[
    'Vue 2 - Advanced Guide',
    'Vue 3 - Basic Guide',
    'Vue 4 - The Mystery'
  ]
})
</script>

<template>
  <h2>first com</h2>
  <hr>
  <div>星期{{   week[6]  }}</div>
  <p>出版了書籍：{{ true? "是" : "否"}}</p>

</template>

<style scoped>
h2{
  color: red;
}
</style>