<!--
vue 컴포넌트 3가지로 이루어져 있음.
1. 템플릿 2. 스크립트 3. 스타일
-->


<template>
<div id="app">
  <router-view />
</div>
</template>
<!-- <template>
  <div id="app">
    <button class="btn btn-primary">Button</button>
    ...
   </div>
</template> -->

<script>
export default {
  name: 'App'
}
</script>
<!--
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
-->
