# 水平垂直居中

<vuep template="#lever-vertical-center"></vuep>
<script v-pre type="text/x-template" id="lever-vertical-center">
<style>
.lever-vertical-center {
  height: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.lever-vertical-center .child{
  width: 100px;
  height: 100px;
  border: 2px solid #ccc;
}
</style>
<template>
<div class="lever-vertical-center">
  <div class="child"></div>
</div>
</template>
<script>
</script>