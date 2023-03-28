<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import PageFoot from './components/PageFoot.vue'
</script>

<template>
  <div class="main">
    <HelloWorld />
    <PageFoot />
  </div>
</template>

<style scoped>
.main{
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>
