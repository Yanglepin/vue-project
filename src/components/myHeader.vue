<template>
  <div class="myHeader">
    <h1>{{title}}</h1>
  </div>
</template>
<script>
export default {
  // 组件标签的名字
  name: 'my-header',
  props: {
    title: String
  }
}
</script>
<style>
.myHeader{
  height: 0.9rem;
  line-height: 0.9rem;
  background-color: #b70419;
}
h1{
  margin: 0;
  font-size: 0.35rem;
  color: #ffffff;
}
</style>
