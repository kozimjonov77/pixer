<template>
    <button class="buttons">
        {{ text }}
    </button>
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
    text: String
})
</script>

<style scoped>
    .buttons{
        background: #00BAFC;
        padding: 8px 16px;
        color: white;
        font-weight: bold;
        font-size: 15px;
        border: none;
        border-radius: 8px;
        cursor: pointer;
    }
</style>