<template>
    <div class="flex w-screen items-center justify-between lg:py-7 lg:px-20 px-2 border border-slate-200 h-10 lg:text-sm text-xs ">
        <div class="w-1/6">
            <img src="../assets/img/logo.png" alt="" class="w-5/6"  >
        </div>
        <div class="flex md:items-center w-5/6  lg:w-3/5 md:w-5/6 md:flex justify-end">
          <!-- lk -->
          <div :class="active ? 'flex flex-col' : 'hidden'" class="md:items-center p-[15px] rounded  top-[50px] right-[10px] md:p-[0px] md:top-[0px] md:right-[0px] md:h-[0px] md:static absolute bg-white lg:w-3/5 md:w-5/6 md:flex justify-between z-30" >
              <a href="/" id="" name="" class="text-indigo-900	 hover:text-teal-500 py-[5px] md:py-[0px]   ">BERANDA</a>
              
                  <!-- Dropdown toggle button -->
              <button @click="show = !show" class=" color flex items-center rounded-md focus:outline-none my-[5px]" >
                <a href="progam" class="md:mr-1 mr-6 text-indigo-900 hover:text-teal-500">PROGAM</a>
                <svg class="mt-1" width="11" height="7" viewBox="0 0 11 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1.95709 1.72754L5.95709 5.72754L9.95709 1.72754" stroke="#1E2D66" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </button>

              <!-- Dropdown menu -->
              <div
                v-show="show"
                class="py-2 mt-2 bg-white rounded-md shadow-lg lg:absolute lg:top-[60px] lg:right-[32%] z-20">
                <router-link to="pdakwah"  class="block px-4 py-2 text-indigo-900	 hover:text-teal-500 hover:bg-blue-900 hover:text-indigo-100">DAKWAH DAN KEUMATAN</router-link>
                <router-link to=""  class="block px-4 py-2 text-indigo-900	 hover:text-teal-500 hover:bg-blue-900 hover:text-indigo-100">SOSIAL</router-link>
                <router-link to="kemanusiaan"  class="block px-4 py-2 text-indigo-900	 hover:text-teal-500 hover:bg-blue-900 hover:text-indigo-100">KEMANUSIAAN</router-link>
                
              </div>
            
              <a href="layanan" id="" name="" class="text-indigo-900 hover:text-teal-500 py-[5px] md:py-[0px] 	 ">LAYANAN</a>
              <a href="ARTIKEL" id="" name="" class="text-indigo-900 hover:text-teal-500 py-[5px] md:py-[0px] 	 ">ARTIKEL</a>
              <a href="tentangkami" id="" name="" class="text-indigo-900 hover:text-teal-500 py-[5px] md:py-[0px] 	 ">TENTANG KAMI</a>  
              
          </div>
          <!-- donasi -->
          <div class="flex items-center ml-[15px]">
              <a class="" href="">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="stroke-indigo-900 hover:stroke-teal-500 " width="20px">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />    
                  </svg>
              </a>
              <a href="" id="" name="" class="text-white hover:bg-teal-500 bg-indigo-900 px-2 m-1 ml-[20px]  md:px-7 md:py-1 border rounded ">DONASI</a>
          </div>
      </div>
        <!-- toggle humburger menu -->
        <!--  -->
          <button id="hamburger " name="hamburger" class="flex flex-col md:hidden relative mr-5 active:animate-bounce" @click="toggleHamburgerButton">
            <span class="px-3 h-1 bg-neutral-900 ml-2 mb-1 "></span>
            <span class="px-3 h-1 bg-neutral-900 ml-2 mb-1 "></span>
            <span class="px-3 h-1 bg-neutral-900 ml-2 mb-1 "></span>
          </button>
          
    </div>
</template>

<script >
  // hamburger
  import { ref } from 'vue';
  export default {
    setup() {
      let active = ref(false);
      let show = ref(false);
      const toggleHamburgerButton = () => (active.value = !active.value);
      return { active,show, toggleHamburgerButton };

    },
  };

</script>

<style setup>
  .color:hover{
    color: rgb(20 184 166);
  }
</style>
