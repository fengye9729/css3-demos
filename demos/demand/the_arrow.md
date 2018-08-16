# css3 画小箭头

<vuep template="#the_arrow"></vuep>
<script v-pre type="text/x-template" id="the_arrow">
<style>
.the_arrow {
  position: relative;
}
/*箭头向上*/
.arrow-up {
  width:0;
  height:0;
  border-left:30px solid transparent;
  border-right:30px solid transparent;
  border-bottom:30px solid #0066cc;
}
/*箭头向下*/
.arrow-down {
  width:0;
  height:0;
  border-left:30px solid transparent;
  border-right:30px solid transparent;
  border-top:30px solid #0066cc;
}
/* 或者旋转 */
</style>
<template>
<div class="the_arrow">
  <div class="arrow-up"></div>
  ---
  <div class="arrow-down"></div>
</div>
</template>
<script>
</script>