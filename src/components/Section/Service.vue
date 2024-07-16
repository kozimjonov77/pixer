<template>
    <section class="services container">
        <div>
             <div>
                <Headings heading="Xizmatlar"/>
                <Headings descript="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar"/>
            </div>
            <div class="cards">
                    <div>
                        <Card img="./src/assets/images/img/img1.png" title="Vebsayt tuzish" text="lorem ipsum"/>
                    </div>
                    <div>
                        <Card img="./src/assets/images/img/img2.png" title="Telegram bot" text="lorem ipsum"/>
                    </div>
                    <div>
                        <Card img="./src/assets/images/img/img3.png" title="SMM" text="lorem ipsum"/>
                    </div>
                    <div>
                    <Card img="./src/assets/images/img/img4.png" title="Grafik dizayn" text="lorem ipsum"/>
                </div>
                <div>
                    <Card img="./src/assets/images/img/img5.png" title="CRM tizimlar" text="lorem ipsum"/>
                </div>
            </div>
            <div class="button">
                <Buttons text="Buyurtma berish"/>
                <a href="" class="link">Xizmatlar sahifasiga o’tish</a>
            </div>
        </div>
    </section>
</template>

<script setup>
import Headings from '../Common/Headings.vue'
import Card from '../Cards/Card.vue'
import Buttons from '../Common/Buttons.vue'
</script>

<style scoped>
.services{
    margin-top: 56px;
}

.cards{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 70px;
}

.button{
    margin: 40px 0;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
}

.link{
    color: #00BAFC;
    font-weight: 400;
    font-size: 16px;
    text-align: center;
    font-family: sans-serif;
}
</style>