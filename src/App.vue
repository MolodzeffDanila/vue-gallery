<template>
  <div id="app">
    <Header msg="Welcome to the Vue.js App!" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  
}

:root {
  --index: calc(1vw + 1vh)
}

body {
    margin: 0;
    background-color: #1f1f1f;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

</style>
<script setup lang="ts">
import Header from "@/components/Header.vue";
</script>