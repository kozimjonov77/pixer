<template>
        <div class="flex justify-center items-center gap-8 mt-6 mb-12">
            <img v-if="position === 'left'" :src="img" alt="rasm bo`lishi kerak edi">
            <div>
                <p class="font-bold text-xl items-center"> {{ title }} </p>
                <p class="font-normal text-base max-w-[493px]"> {{ text }} </p>
            </div> 
            <img v-if="position === 'right'" :src="img" alt="rasm bo`lishi kerak edi">
        </div>
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
    img: String,
    title: String,
    text: String,
    position: Boolean
})
</script>

<style scoped>
</style>