<template>
  <img class="header" src="../assets/header.png"/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({});
</script>

<style scoped>
  .header {
    width: calc(var(--index) * 20);
    -webkit-mask-image: radial-gradient(rgba(31,31,31,1) calc(var(--index) * 4), rgba(31,31,31,0) calc(var(--index) * 12));
    
    mask-image: radial-gradient(rgba(31,31,31,1) calc(var(--index) * 4), rgba(31,31,31,0) calc(var(--index) * 12));
  }
</style>
