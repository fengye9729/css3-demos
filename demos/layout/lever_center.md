# 水平居中

<vuep template="#lever-center"></vuep>
<script v-pre type="text/x-template" id="lever-center">
<style>
// 行内元素
.inline-child {
  text-align: center;
}
// 块状元素
.block-element {
  width: 100px;
  height: 100px;
  border: 2px solid #ccc;
  margin: 0 auto;
}
// 多个块状元素
.block-children {
  text-align: center
}
.block-children .child {
  width: 100px;
  height: 100px;
  border: 2px solid #ccc;
  display: inline-block;
}
</style>
<template>
<div class="lever-center">
  <div class="inline-child">
    <span>inline-child</span>
  </div>
  <div class="block-child">
    <div class="block-element"></div>
  </div>
  <div class="block-children">
    <div class="child"></div>
    <div class="child"></div>
  </div>
</div>
</template>
<script>
</script>