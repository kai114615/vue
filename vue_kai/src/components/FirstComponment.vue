<script setup>
import { onBeforeMount, onMounted } from 'vue';

// const week = ["日", "一", "二", "三", "四", "五", "六"]
// const author = ref({
//   books:[
//     'Vue 2 - Advanced Guide',
//     'Vue 3 - Basic Guide',
//     'Vue 4 - The Mystery'
//   ]
// })


onBeforeMount(()=>{
  console.log('before-mount')
})
onMounted(() => {
  console.log('mounted')
  const myH = document.querySelector('#theH')
  console.log(myH.textContent)
})
</script>


<template>
  <h2 id="theH">first com</h2>
  <hr>
  <!-- <hr>
  <div>星期{{   week[6]  }}</div>
  <p>出版了書籍：{{ true? "是" : "否"}}</p> -->

</template>

<style scoped>
h2{
  color: red;
}
</style>