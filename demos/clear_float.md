# 清除浮动

<vuep template="#clear-float"></vuep>
<script v-pre type="text/x-template" id="clear-float">
<style>
.clear-float::after {
  content: '';
  display: block;
  clear: both;
}
.clear-float div {
  width: 100px;
  height: 100px;
  background: #ccc;
  float: left;
}
</style>
<template>
<div class="clear-float">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
</template>
<script>
</script>