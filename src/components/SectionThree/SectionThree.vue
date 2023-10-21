<template>
    <section>
        <div class="container mx-auto">
            <div class="flex justify-between items-center">
                <h1 class="text-[16px] md:text-[24px] font-Roboto font-bold lg:ml-5 xl:ml-0">Tavsiya etilgan ijara</h1>
                <button class="mr-4 py-1 px-3 rounded-md md:mr-0 lg:mr-4 border text-[12px] md:text-[16px]">Hammasi</button>
            </div>
            <div class="flex flex-wrap lg:flex-col-4 justify-center items-center gap-10 my-10">
                <div v-for="(ts, ind) in displayedInformation" :key="ind" class="w-[300px] lg:w-[290px] border p-2 bg-white">
                    <img src="../../assets/images/xona2.png" alt="image">
                   <div class="grid gap-2">
                    <h1 class="text-[24px] font-bold">{{ ts.price }}</h1>
                    <p class="font-[600] text-[14px]">{{ ts.title }}</p>
                    <p class="text-[10px] text-gray-500">{{ ts.description }}</p>
                    <p class="text-[10px] text-gray-500">{{ ts.day }}</p>
                    <div class="flex gap-6">
                        <div class="flex items-center">
                            <i :class="ts.icon1" class="font-bold"></i>
                            <p class="text-[12px]">{{ ts.num1 }}</p>
                        </div>
                        <div class="flex items-center">
                            <i :class="ts.icon2" class="font-bold"></i>
                            <p class="text-[12px]">{{ ts.num2 }}</p>
                        </div>
                        <div class="flex items-center">
                            <i :class="ts.icon3" class="font-bold"></i>
                            <p class="text-[12px]">{{ ts.num3 }}</p>
                        </div>
                    </div>
                   </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
    import { ref, onMounted, reactive, computed } from "vue";
    import { tanlangan_savdo } from '../../constants/tanlangan_savdo';
    const ts = ref(tanlangan_savdo)

    const displayedInformation = computed(() => ts.value.slice(0, 4));
</script>

<style lang="scss" scoped>

</style>