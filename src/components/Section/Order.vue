<<template>
    <section class="bg-[#00BAFC] py-14">
        <div>
            <Headings variant="white" heading="Biz qanday ishlaymiz?"/>
            <Headings variant="white" descript="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar"/>
        </div>
        <div class="mx-auto max-w-[348px]">
            <form class="grid grid-cols-1 p-6 bg-white rounded-lg">
                <input class="p-4 font-normal text-black bg-[#F3F3F3] rounded-lg w-full" required	type="text"	id="first-name"	placeholder="Ismingiz"/>
                <input class="p-4 font-normal text-black bg-[#F3F3F3] my-4 rounded-lg w-full" required	type="number" id="number" placeholder="Tel raqamingiz"/>
                <select class="p-4 font-normal text-black bg-[#F3F3F3] rounded-lg w-full">
                    <option value="">Xizmat turi</option>
                    <option value="">Payme</option>
                    <option value="">Click</option>
                    <option value="">naxt</option>
                </select>
                <div class="text-center mt-4">
                    <Buttons text="Buyurtma berish"/>
                </div>
                
            </form>
        </div>
        
    </section>
</template>

<script setup>
import Headings from '../Common/Headings.vue'
import Buttons from '../Common/Buttons.vue'
</script>