<script setup lang="ts">
  import axios from 'axios'
  const openDoor = () => {
    axios.get("api/openDoor/open").then((res) => {
      console.log(res)
    })
  }
</script>

<template>
  <button @click="openDoor()">开门</button>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
