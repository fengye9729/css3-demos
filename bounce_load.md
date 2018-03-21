弹跳加载

<vuep template="#ring-rotating"></vuep>
<script v-pre type="text/x-template" id="ring-rotating">
<style>
.bouncing-loader {
  display: flex;
  justify-content: center;
}
.bouncing-loader div {
  width: 2rem;
  height: 2rem;
  background: #8388aa;
  border-radius: 50%;
  margin: 3rem 0.2rem;
  animation: bouncing-loader 0.6s infinite alternate;
}
.bouncing-loader div:nth-child(2) {
  animation-delay: 0.2s;
}
.bouncing-loader div:nth-child(3) {
  animation-delay: 0.4s;
}
</style>
<template>
<div class="bouncing-loader">
  <div></div>
  <div></div>
  <div></div>
</div>
</template>
<script>  
</script>
</script>