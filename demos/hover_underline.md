# 悬停下划线

<vuep template="#hover_underline"></vuep>

<script v-pre type="text/x-template" id="hover_underline">
<style>
.hover_undeline {
  position:relative;
  display: inline-block;
}

.hover_undeline::after {
  position: absolute;
  width: 100%;
  content: '';
  bottom: 0;
  left: 0;
  background: #8e8e8e;
  height: 2px;
  transform: scaleX(0);
  transition: transform 0.25s ease-out;
}

.hover_undeline:hover:after {
  transform: scaleX(1);
}

</style>
<template>
<div class="hover_undeline">hello world</div>
</template>
<script>
</script>
</script>