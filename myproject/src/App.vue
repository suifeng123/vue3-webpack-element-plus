<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Test></Test>
  <el-button type="primary">普通那妞</el-button>
</template>

<script>
import Test from "@/components/MyC.vue"	

export default {
  name: 'App',
  components: {
	  Test
  }
}
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
