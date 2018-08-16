# chrome 中设置小于 12px 的字体

<vuep template="#font_size"></vuep>
<script v-pre type="text/x-template" id="font_size">
<style>
.font_size {
  cursor: pointer;
  font-size: 10px;
  display: inline-block;
  transform: scale(0.9);
}
</style>
<template>
<div class="font_size">
  这是一行 「小于12px」的字
</div>
</template>
<script>
</script>