# 环形旋转
<vuep template="#blink"></vuep>

<script v-pre type="text/x-template" id="blink">
<style>
.circle {
  width: 2rem;
  height: 2rem;
  border-radius: 50%;
  margin: 0 auto;
  border: 4px solid rgba(0,0,0,0.1);
  border-left-color: #789aaa;
  animation: donut 1.2s linear infinite;
}

@keyframes donut {
  0% {
    transform: rotate(0deg)
  }
  100% {
    transform: rotate(360deg)
  }
}

</style>
<template>
<div class="circle">
</div>
</template>
<script>
</script>
</script>