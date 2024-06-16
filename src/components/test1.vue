<template>
  <div class="test1">
    <h2>姓名:{{name}}</h2>
    <button @click="showTel">展示联系方式</button>
  </div>
</template>

<script lang="ts" setup name="person123">
 let name='张三'
 let tel='13888888888'

 function showTel(){
  alert(tel)
 } 
</script> 

<style scoped lang="scss">
</style>