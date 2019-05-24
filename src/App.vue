
<template>
  <div id="app">
    <my-header title="首页"></my-header>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>
<script>
// 引用头部组件
import myHeader from './components/myHeader'
export default {
  name: 'App',
  components: {
    'my-header': myHeader
  }
}
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
