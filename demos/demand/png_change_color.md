# png 图片如何改颜色

<vuep template="#png_change_color"></vuep>
<script v-pre type="text/x-template" id="png_change_color">
<style>
.icon {
  display: inline-block;
  width: 20px; 
  height: 20px;
  overflow: hidden;
  color: red;
}
.icon-del {
  background: url(https://www.zhangxinxu.com/study/201606/delete.png) no-repeat center;
}
.icon > .icon {
  position: relative;
  left: -20px;
  border-right: 0px solid transparent;
  -webkit-filter: drop-shadow(20px 0);
  filter: drop-shadow(20px 0);  
}
</style>
<template>
<div class="png_change_color">
  <p><strong>原始图标</strong></p>
  <i class="icon icon-del"></i>
  <p><strong>可以变色的图标</strong></p>
  <i class="icon"><i class="icon icon-del"></i></i>
</div>
</template>
<script>
</script>