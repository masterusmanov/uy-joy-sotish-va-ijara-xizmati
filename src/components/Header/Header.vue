<template>
    <header>
        <div class="container mx-auto">
            <div class="h-[70px] flex justify-beetwen items-center gap-6">
                <div class="w-1/2 flex justify-center md:justify-between md:ml-5 lg:ml-0 items-center gap-10">
                    <div class="flex items-center">
                        <img src="../../assets/images/logo.svg" alt="">
                        <h2 class="text-[24px] ml-2"><b>fast</b><span>home</span></h2>
                    </div>
                    <a href="#" class="text-[14px] font-Roboto hidden lg:block">Bosh sahifa</a>
                    <a href="#" class="text-[14px] font-Roboto hidden lg:block">Sotuvda</a>
                    <a href="#" class="text-[14px] font-Roboto hidden lg:block">Ijaraga</a>
                    <a href="#" class="text-[14px] font-Roboto hidden lg:block">Kunlik ijara</a>
                    <a href="#" class="text-[14px] font-Roboto hidden lg:block">Noturar</a>
                    <a href="#" class="text-[14px] font-Roboto hidden lg:block">Loyihalar</a>
                </div>
                <div class="w-1/2 grid justify-end mr-5 md:mr-0 items-center lg:hidden">
                  <button id="dropdownDefaultButton" data-dropdown-toggle="dropdown" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-2 text-center inline-flex items-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800" type="button"><i class='bx bx-menu text-3xl'></i>
                  </button>
                  <!-- Dropdown menu -->
                  <div id="dropdown" class="z-10 hidden bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700">
                      <ul class="py-2 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownDefaultButton">
                        <li>
                          <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Sotuvda</a>
                        </li>
                        <li>
                          <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Ijaraga</a>
                        </li>
                        <li>
                          <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Kunlik ijara</a>
                        </li>
                        <li>
                          <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Noturar</a>
                        </li>
                        <li>
                          <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Loyihalar</a>
                        </li>
                      </ul>
                  </div>
                </div>
                <div class="hidden md:w-1/2 lg:flex justify-end items-center gap-6 mr-5">
                    <a href="#" class="bg-red-500 text-white px-3 rounded-md">Reklama</a>
                    <img src="https://w7.pngwing.com/pngs/178/595/png-transparent-user-profile-computer-icons-login-user-avatars-thumbnail.png" class="w-[25px] rounded-full" alt="">
                </div>
            </div>
        </div>
    </header>
</template>

<script setup>
  import { onMounted } from 'vue'
  import { initDropdowns } from 'flowbite'

  onMounted(() => {initDropdowns()})
</script>

<style lang="scss" scoped>

</style>