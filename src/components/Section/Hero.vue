<template>
    <section class="container flex justify-between items-center gap-36 ">
        <div>
            <div>
                <h1 class="font-bold text-3xl">Biznesingizni keyingi bosqichga olib chiqing</h1>
                <p class="font-normal text-base my-4">Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar</p>
                <Buttons text="Xizmatlar bilan tanishish"/>
            </div>
        </div>
        <div>
            <iframe class="rounded-md" width="560" height="315" src="https://www.youtube.com/embed/zIwLWfaAg-8?si=CqvEkq7IDaD8CCma" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>
</template>

<script setup>
import Buttons from '../Common/Buttons.vue'
</script>
