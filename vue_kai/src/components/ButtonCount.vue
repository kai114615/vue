<script setup>
import { nextTick, ref } from 'vue';

const count = ref(100)
const add = async ()=>{
    // console.log(count.value)   // 響應式的變數
    count.value++
    await nextTick()
    const btn = document.querySelector('button')
    console.log(btn.textContent)
}
const week = ["日", "一", "二", "三", "四", "五", "六"]
</script>





<template>
<div>
    <div>星期{{   count   }}</div>

    <button @click="add">{{ count }}</button>
    <hr>
    <!-- {{ if (true) { return 'Hello' } }} -->
    <!-- {{ new Date().toLocaleDateString() }}
    {{ let name = 'Jack’ }}
    {{ i+=1 }} -->




</div>
</template>


<style>
</style>

