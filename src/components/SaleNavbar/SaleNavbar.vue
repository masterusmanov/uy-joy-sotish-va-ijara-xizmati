<template>
    <section>
        <div class="container mx-auto"> 
            <div class="grid md:flex flex-wrap md:justify-start items-center gap-2 md:gap-6 bg-white py-2 px-2">
                <div>
                    <select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                    <option selected disabled>Hudud</option>
                    <option value="Pop">Namangan shahar</option>
                    <option value="Pop">Davlatobod</option>
                    <option value="Pop">Pop</option>
                    <option value="Pop">Kosonsoy</option>
                    <option value="Chust">Chust</option>
                    <option value="Mingbuloq">Mingbuloq</option>
                    <option value="Yaangiqqo'rg'on">Yangiqo'rg'on</option>
                    <option value="Yaangiqqo'rg'on">To'raqo'rg'on</option>
                    <option value="Yaangiqqo'rg'on">Chortoq</option>
                    <option value="Yaangiqqo'rg'on">Uychi</option>
                    <option value="Yaangiqqo'rg'on">Uchqo'rg'on</option>
                    <option value="Yaangiqqo'rg'on">Norin</option>
                    </select>
                </div>
                <div>                
                    <select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                    <option selected disabled>Uy-joy</option>
                    <option value="US">Uy</option>
                    <option value="CA">Xonadon</option>
                    <option value="FR">Noturar</option>
                    <option value="DE">Ijara</option>
                    </select>
                </div>
                <div>                
                    <select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                    <option selected disabled>Narxlari</option>
                    <option value="US">Uy</option>
                    <option value="CA">Xonadon</option>
                    <option value="FR">Noturar</option>
                    <option value="DE">Ijara</option>
                    </select>
                </div>
                <div>                
                    <select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                    <option selected disabled>Xajmi (m2)</option>
                    <option value="US">Uy</option>
                    <option value="CA">Xonadon</option>
                    <option value="FR">Noturar</option>
                    <option value="DE">Ijara</option>
                    </select>
                </div>
                <div>                
                    <select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                    <option selected disabled>Xonalar soni</option>
                    <option value="US">Uy</option>
                    <option value="CA">Xonadon</option>
                    <option value="FR">Noturar</option>
                    <option value="DE">Ijara</option>
                    </select>
                </div>
            </div>
            <div class="hidden md:flex">
                <input type="text" placeholder="Search" class="h-[40px]">
            </div>
        </div>
    </section>
</template>

<script setup>
  import { ref, onMounted } from 'vue'
  
</script>

<style lang="scss" scoped>
</style>