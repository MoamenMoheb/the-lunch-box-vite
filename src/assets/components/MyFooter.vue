<script setup>
    import Location from './Location.vue';
</script>

<template>
    <footer class="bg-gray-800 text-white p-4">
        <div class="container mx-auto flex justify-between">

            <div class="flex flex-col gap-2">
                <a href="https://www.instagram.com/thelunchboxsandwichshop/" class="bg-blue-500 hover:bg-blue-700 text-white font-bold size-fit p-2 rounded self-center">instagram</a>
                <a href="tel:7802436690" class="self-center">(780) 243-6690</a>
                <p>Mon-Fri | 8am - 6pm Sat | 10-6 Sun | 11-5</p>
            </div>
            <div class="flex flex-col gap-2">
                <Location />
                <a href="#" class="bg-blue-500 hover:bg-blue-700 text-white font-bold size-fit p-2 rounded self-center">Back to top</a>
            </div>
        </div>
    </footer>
</template>