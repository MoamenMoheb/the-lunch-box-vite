<script setup>
  import Orderbutton from './Orderbutton.vue'
  import banner from '../images/banner.avif'
</script>

<template>
    <div class="h-screen bg-no-repeat bg-center bg-cover" :style="{ backgroundImage: `url(${banner})` }">
        <div class="text-6xl font-bold text-white absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">Never Fancy, Always Tasty</div>
    </div>
    <Orderbutton class="absolute bottom-0 left-1/2 transform -translate-x-1/2" />
</template>

