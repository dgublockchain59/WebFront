<!-- 컴포넌트에 vue파일을 추가하고, index.js에서 라우터에
이 컴포넌트를 추가한다. -->

<template>
<div class="panel panel-default">
  <div class="panel-heading">Panel heading without title</div>
  <div class="panel-body">
    Panel content
  </div>
</div>
</template>

<script>
export default {
  name: 'Example',
  data() {
    return {
      msg: 'Basic panel example'
    }
  }
}
</script>
