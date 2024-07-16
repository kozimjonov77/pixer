<template>
    <section class="work container">
             <div>
                <Headings heading="Biz qanday ishlaymiz?"/>
                <Headings descript="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar"/>
            </div>
            <div>
                <Frame img="./src/assets/images/img/frame1.png" title="Talablarni aniqlab chiqamiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img_right="./src/assets/images/img/frame2.png" title_right="Bir necha yechimlarni taklif qilamiz" text_right="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img="./src/assets/images/img/frame3.png" title="Loyiha uchun vaqt belgilaymiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img_right="./src/assets/images/img/frame4.png" title_right="A’lo sifat bilan bajarib topshiramiz" text_right="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
                <Frame img="./src/assets/images/img/frame5.png" title="Qo’llab-quvvatlab boramiz" text="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
            </div>
            <div class="text-center mb-14"> <Buttons text="Buyurtma berish"/> </div>
    </section>
</template>

<script setup>
import Headings from '../Common/Headings.vue'
import Frame from '../Cards/Frame.vue'
import Buttons from '../Common/Buttons.vue'
</script>

<style scoped>

</style>