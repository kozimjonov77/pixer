<template>
    <div>
        <div class="service">
            <h2 class="headings font-bold text-2xl"> {{ heading }} </h2>
            <p class="text font-normal text-base items-center my-4"> {{ descript }} </p>
        </div>
        <div class="service">
            <h2 class="headings font-bold text-2xl text-white"> {{ heading_white }} </h2>
            <p class="text font-normal text-base items-center my-4 text-white"> {{ descript_white }} </p>
        </div>
    </div>
    
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
    heading: String,
    descript: String,
    heading_white: String,
    descript_white: String
})
</script>

<style scoped>
.service{
    text-align: center;
    padding: 0 280px;
}
</style>