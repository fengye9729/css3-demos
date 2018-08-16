# 修改鼠标手势图标

<vuep template="#current_color"></vuep>
<script v-pre type="text/x-template" id="current_color">
<style>
.icon {
  display: inline-block;
  width: 16px; 
  height: 20px;
  background-image: url(test.png);
  background-color: currentColor; /* 该颜色控制图标的颜色 */
  background-position: 0 0;
}
.link:hover {
  color: #333; /* 虽然改变的是文字颜色，但是图标颜色也一起变化了 */
}
</style>
<template>
<div class="current_color">
  <a href="##" class="link"><i class="icon"></i>返回</a>
</div>
</template>
<script>
</script>