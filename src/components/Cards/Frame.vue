<template>
    <div>
        <div class="flex justify-center items-center gap-8 mt-6 mb-12">
            <img :src="img">
            <div>
                <p class="font-bold text-xl items-center"> {{ title }} </p>
                <p class="font-normal text-base max-w-[493px]"> {{ text }} </p>
            </div> 
        </div>
        <div class="flex justify-center items-center gap-8 mt-6 mb-12">
            <div>
                <p class="font-bold text-xl items-center"> {{ title_right }} </p>
                <p class="font-normal text-base max-w-[493px]"> {{ text_right }} </p>
            </div> 
            <img :src="img_right">
        </div>
    </div>
    
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
    img: String,
    title: String,
    text: String,
    img_right: String,
    title_right: String,
    text_right: String,
})
</script>

<style scoped>
</style>