<template>
    <section class="work container">
             <div>
                <Headings variant="black" heading="Biz qanday ishlaymiz?"/>
                <Headings variant="black" descript="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar"/>
            </div>
            <div>
                <Frame img="./src/assets/images/img/frame1.png" position="left" title="Talablarni aniqlab chiqamiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img="./src/assets/images/img/frame2.png" position="right" title="Bir necha yechimlarni taklif qilamiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img="./src/assets/images/img/frame3.png" position="left" title="Loyiha uchun vaqt belgilaymiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img="./src/assets/images/img/frame4.png" position="right" title="A’lo sifat bilan bajarib topshiramiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img="./src/assets/images/img/frame5.png" position="left" title="Qo’llab-quvvatlab boramiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
            </div>
            <div class="text-center mb-14"> <Buttons text="Buyurtma berish"/></div>
    </section>
</template>

<script setup>
import Headings from '../Common/Headings.vue'
import Frame from '../Cards/Frame.vue'
import Buttons from '../Common/Buttons.vue'
</script>

<style scoped>

</style>