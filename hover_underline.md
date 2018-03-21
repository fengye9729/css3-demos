<vuep template="#hover_underline"></vuep>

<script v-pre type="text/x-template" id="hover_underline">
<style>
p {
  position:relative;
  display: inline-block;
}
p:after {
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
p:hover:after {
  transform: scaleX(1);
}
</style>
<template>
<p>hello world</p>
</template>
</script>