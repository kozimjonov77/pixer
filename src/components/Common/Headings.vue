<template>
        <div class="service">
            <h2 :class="cardsStyles()" class="headings font-bold text-2xl"> {{ heading }} </h2>
            <p :class="cardsStyles()"  class="text font-normal text-base items-center my-4"> {{ descript }} </p>
        </div>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps({
    heading: String,
    descript: String,
    variant: String
})

const cardsStyles = () => {
    switch (props.variant) {
        case 'black':
            return 'black'
            break;
        case 'white':
            return 'white'
            break
    }
}
</script>

<style scoped>
.service{
    text-align: center;
    padding: 0 280px;
}

.black{
    color: #000000;
}

.white{
    color: #FFFFFF;
}
</style>