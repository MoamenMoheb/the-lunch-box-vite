<script setup>
  import Catering from './Catering.vue'
  import Brief from './Brief.vue'

</script>

<template>
    <div class="flex items-center justify-between bg-white m-10">
        <img src="../images/Menu1_Cropped.jpg" alt="menu1" class="w-1/3 mx-auto">
        <img src="../images/Menu2_Cropped.jpg" alt="menu2" class="w-1/3 mx-auto">
    </div>
    <div class="flex items-center justify-betwee">
        <p class="bg-gray-800 text-white m-auto text-center items-center justify-center p-10 rounded">
            <Catering />
        </p>
        <p class="bg-gray-800 text-white m-auto text-center items-center justify-center p-10 rounded">
            <Brief />
        </p>
    </div>
</template>