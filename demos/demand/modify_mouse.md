# 修改鼠标手势图标

<vuep template="#modify-mouse"></vuep>
<script v-pre type="text/x-template" id="modify-mouse">
<style>
.pointer{
  cursor: pointer;
}.wait {
  cursor: wait;
}.text {
  cursor: text;
}.move {
  cursor: move;
}.not-allowed {
  cursor: not-allowed;
}.zidingyi {
  cursor: url(' # '); // # = 光标文件地址      (注意文件格式必须为：.cur 或 .ani)
}
</style>
<template>
<div class="modify-mouse">
  <a class="pointer">放上来pointer</a> |
  <a class="wait">放上来wait</a> |
  <a class="text">放上来text</a> |
  <a class="move">放上来move</a> |
  <a class="not-allowed">放上来not-allowed</a> |
  <a class="zidingyi">放上来「自定义」</a>
</div>
</template>
<script>
</script>