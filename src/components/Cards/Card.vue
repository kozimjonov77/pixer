<<template>
    <div class="card">
       <img :src="img"> 
       <h3 class="title"> {{ title }} </h3>
       <p class="text"> {{ text }} </p>
    </div>
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
    img: String,
    title: String,
    text: String
})
</script>

<style  scoped>
.card{
    padding: 24px 57px;
    background: white;
    box-shadow: 0px 10px 10px -5px rgba(0, 0, 0, 0.2);
}

.title{
    font-weight: 700;
    font-size: 20px;
    text-align: center;
    font-family: sans-serif;
    color: #000000;
    margin-top: 16px;
    margin-bottom: 16px;
}

.text{
    font-weight: 400;
    font-size: 16px;
    text-align: center;
    font-family: sans-serif;
    color: #000000;
}
</style>