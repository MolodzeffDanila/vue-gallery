<template> 
  <header class="hero-section">
    <img class="header-img" src="../assets/bg2.jpg"/>
    <div class="container">
      <div class="header">
        <h1 class="main-title">Blade Runner 2049</h1>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({});
</script>

<style scoped>
  .container {
    padding: 0 5vw;
  }

  .main-title {
    font-size: calc(var(--index) * 5);
    color: beige;

    position: absolute; 
    width: min-content;

    bottom: 12vh;
    line-height: 0.8;
    letter-spacing: 0.15em;

    font-family: 'outfit-c';
  }

  .hero-section {
    height: 80vh;
  }

  .header-img {
    margin-left: 37vw;
    width: calc(var(--index) * 35);

    margin-top: 10vh;

    position: absolute;

    -webkit-mask-image: 
    linear-gradient(to top, black 80%, transparent 100%),
    linear-gradient(to bottom, black 80%, transparent 100%),
    linear-gradient(to left, black 80%, transparent 100%),
    linear-gradient(to right, black 80%, transparent 100%);
  -webkit-mask-composite: intersect;
  mask-composite: intersect;

  mask-image: 
    linear-gradient(to top, black 80%, transparent 100%),
    linear-gradient(to bottom, black 80%, transparent 100%),
    linear-gradient(to left, black 80%, transparent 100%),
    linear-gradient(to right, black 80%, transparent 100%);
  }
</style>
