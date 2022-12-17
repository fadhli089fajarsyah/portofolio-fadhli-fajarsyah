<template>
    <div class="flex w-screen items-center justify-between xl:py-7 xl:px-20 px-2 border border-slate-200 h-10 xl:text-sm text-xs ">
        <div class="w-1/6">
            <img src="../assets/img/logo.png" alt="" class="w-5/6"  >
        </div>
        <div class="items-center w-5/6  xl:w-3/5 md:w-5/6 flex justify-between ">
            <a href="index" id="" name="" class="text-indigo-900	 hover:text-teal-500 hidden md:flex  ">BERANDA</a>
            <select name="" class="text-indigo-900 hover:text-teal-500 hidden md:flex	">
                <option href="progam" CLASS="text-teal-500 hidden md:flex" > PROGRAM</option>
                <option href="pdakwah" class="text-teal-500 hidden md:flex" > a</option>
            </select>
            <a href="layanan" id="" name="" class="text-indigo-900 hover:text-teal-500 hidden md:flex	 ">LAYANAN</a>
            <a href="ARTIKEL" id="" name="" class="text-indigo-900 hover:text-teal-500 hidden md:flex	 ">ARTIKEL</a>
            <a href="tentangkami" id="" name="" class="text-indigo-900 hover:text-teal-500 hidden md:flex	 ">TENTANG KAMI</a>  
            <a class="" href="">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="stroke-indigo-900 hover:stroke-teal-500 " width="20px">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />    
                </svg>
            </a>
            <a href="" id="" name="" class="text-white hover:bg-teal-500 bg-indigo-900 px-2 m-1  md:px-7 md:py-1 border rounded ">DONASI</a>
        </div>
        <!-- toggle humburger menu -->
          <button id="hamburger" name="hamburger" class="flex flex-col md:hidden relative mr-5" @click="toggleHamburgerButton">
            <span class="px-3 h-1 bg-neutral-900 ml-2 mb-1 "></span>
            <span class="px-3 h-1 bg-neutral-900 ml-2 mb-1 "></span>
            <span class="px-3 h-1 bg-neutral-900 ml-2 mb-1 "></span>
          </button>
          <!-- {{ active }} -->
    </div>
</template>

<script setup>
  // hamburger
import {ref} from 'vue';

const active = ref(false);

function toggleHamburgerButton() {
    active.value = !active.value;
}

</script>
