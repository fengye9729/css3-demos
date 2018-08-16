# 0.5px border 如何操作

<vuep template="#border_px"></vuep>
<script v-pre type="text/x-template" id="border_px">
<style>
.border_px {
  position: relative;
}
/* 使用渐变 linear-gradient 来操作，但需要注意浏览器兼容前缀 */
.border_one::after {
  content: " ";
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 1px;
  background-image: linear-gradient(0deg, transparent 50%, #ec0f0f 50%);
}
/* 缩放 scale 处理 */
.border_two::after{
  content: "";
  display: block;
  position: absolute;
  left: -50%;
  top: 50px;
  width: 200%;
  height: 1px;
  background: #ec0f0f;
  -webkit-transform: scale(0.5);
}
/* 使用 background-image 和 css3 的九宫格裁减 */
.border_three::after {
  content: " ";
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  border-top: 1px solid #ec0f0f;
  /* 下面用 stretch 和 round 都可以 */
  /* border-image: url('pic.png') 2 1 1 1 stretch; 
  -webkit-border-image: url('pic.png') 2 1 1 1 stretch; */
}

</style>
<template>
<div class="border_px">
  <div class="border_one">111</div>
  <div class="border_two">222</div>
  <div class="border_three">333</div>
</div>
</template>
<script>
</script>