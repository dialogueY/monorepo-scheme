<!--
 * @Author: yangfeng
 * @Date: 2023-08-16 12:02:44
 * @LastEditors: yangfeng
 * @LastEditTime: 2023-08-16 12:58:09
 * @FilePath: \lerna-pro\packages\package1\src\App.vue
 * @Description: 
-->
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script setup>
import package2 from "package2";
import HelloWorld from './components/HelloWorld.vue'
console.log(package2())
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
