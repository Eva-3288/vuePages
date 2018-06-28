<template>
  <div id="app">
    <img src="./../../assets/logo.png">
    <a href="./../login.html">跳转到登录页</a>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'index'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
