<template>
  <div class="global-bg" />
</template>

<style scoped>
.global-bg {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background: linear-gradient(135deg, #0d0d0d 0%, #1a1a2e 50%, #0d0d0d 100%);
  z-index: -100;
}
.global-bg::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background:
    radial-gradient(circle at 20% 80%, rgba(120, 80, 200, 0.08) 0%, transparent 50%),
    radial-gradient(circle at 80% 20%, rgba(80, 160, 200, 0.08) 0%, transparent 50%),
    radial-gradient(circle at 50% 50%, rgba(200, 100, 80, 0.05) 0%, transparent 70%);
  pointer-events: none;
}
</style>
