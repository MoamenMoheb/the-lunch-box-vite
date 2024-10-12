<template>
  <nav class="bg-gray-800 text-white">
    <ul class="flex justify-between items-center container mx-auto">
      <li class="py-2">
        <img src="../images/logoWhite.png" alt="Logo" class="size-20" />
      </li>
      <li class="mr-6">
        <a href="#" class="text-lg hover:text-gray-300">Home</a>
      </li>
      <li class="mr-6">
        <a href="#" class="text-lg hover:text-gray-300">Menu</a>
      </li>
      <li class="mr-6">
        <a href="#" class="text-lg hover:text-gray-300">About us</a>
      </li>
      <li>
        <Orderbutton />
      </li>
    </ul>
  </nav>
</template>

<script setup>
import Orderbutton from './Orderbutton.vue'
</script>