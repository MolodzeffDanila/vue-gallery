<template>
  <div id="app">
    <Header msg="Welcome to the Vue.js App!" />
    <GalleryWrapper />
  </div>
</template>

<style>

:root {
  --index: calc(1vw + 1vh)
}

@font-face {
	font-family: raleway-c;
	src: url(../src/fonts/raleway-regular.woff2);
}
@font-face {
	font-family: outfit-c;
	src: url(../src/fonts/outfit-regular.woff2);
}

body {
    margin: 0;
    background-color: #1f1f1f;
    width: 100%;
    height: 100%;
    overflow-x: hidden;
}

</style>
<script setup lang="ts">
import Header from "@/components/Header.vue";
import GalleryWrapper from "@/components/GalleryWrapper.vue";
</script>