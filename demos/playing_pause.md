# 播放与暂停

<vuep template="#playing_pause"></vuep>
<script v-pre type="text/x-template" id="playing_pause">
<style>
.btn {
  width: 80px;
  border-radius: 5px;
  text-align: center;
  background: #ccc;
  margin: 10px auto;
  padding: 5px;
}
.animation {
  width: 100px;
  height: 100px;
  margin: 20px auto;
  background: #aaa;
}
@keyframes playing_pause {
  from {
    transform: translateX(-100px);
  }
  to {
    transform: translateX(100px);
  }
}
.animation {
  animation: playing_pause 2s linear infinite alternate;
}
.btn:hover ~ .animation {
  animation-play-state: paused;
}
</style>
<template>
<main>
  <div class="btn">暂停</div>
  <div class="animation"></div>
</main>
</template>
<script>  
</script>
</script>