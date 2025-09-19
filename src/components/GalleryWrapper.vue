<template>
    <div class="gallery-wrapper">
        <li v-for="item in imgs">
        {{ item }}
</li>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'GalleryWrapper',
    data() {
        return {
            imgs: ['header.png', 'BG.jpg', 'ext.jpg']
        };
    }
});
</script>

<style scoped>

</style>