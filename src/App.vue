<script setup>
import { reactive } from 'vue';
const msg = "我是天下第一高手"
const count = 0
const wife = reactive( {
  name:'关晓彤',
  age:28,
  gender:'女'
})

function showWife(){
  alert("我的的妾是杨幂")
}



</script>

<template>

  <h1>{{ msg }}</h1>
  <h2>我的妻子是：{{ wife.name }},她今年{{ wife.age }}岁</h2>
  <button @click="showWife">你的妾是谁</button>


</template>

