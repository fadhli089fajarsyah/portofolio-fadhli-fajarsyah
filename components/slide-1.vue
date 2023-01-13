<template>
    <swiper :navigation="true" :modules="modules" class="mySwiper">
        <swiper-slide><div class="flex items-center justify-between px-[20px] md:px-[70px] ">
            <div class="lg:text-[13px] text-[5px] md:text-[8px]">
                <p class="text-emerald-700">CERITA CERITA SUKSES</p>
                <h1 class="lg:text-[23px] text-[10px] md:text-[17px] text-emerald-700 font-bold">Penyaliran donasi pelita Untuk <br> Negeri,Desa Ciceuri Kab. <br> Bandung Barat</h1>
                <p>Untuk itu, di bulan yang Allah turunkan keberkahan, bulan suci <br> Ramadhan, tim YABI mengerahkan para relawan YABI untuk <br> sama-sama menggalangkan donasi. Dimana donasi yang <br> terkumpul tersebut akan dibuat paket sembako yang siap <br> didistribusikan kepada masyarakat terdampak Covid-19. Dengan <br> adanya paket sembako ini diharapkan dapat meringankan <br> beban mereka para pejuang di keluarganya.</p>
            </div>
                <img class="h-auto w-[50%]" src="../assets/img/sd1.png" alt="">
            </div>
        </swiper-slide>
        <swiper-slide><div class="flex items-center justify-between px-[20px] md:px-[70px] ">
            <div class="lg:text-[13px] text-[5px] md:text-[8px]">
                <p class="text-emerald-700">CERITA CERITA SUKSES</p>
                <h1 class="lg:text-[23px] text-[10px] md:text-[17px] text-emerald-700 font-bold">Penyaliran donasi pelita Untuk <br> Negeri,Desa Ciceuri Kab. <br> Bandung Barat</h1>
                <p>Untuk itu, di bulan yang Allah turunkan keberkahan, bulan suci <br> Ramadhan, tim YABI mengerahkan para relawan YABI untuk <br> sama-sama menggalangkan donasi. Dimana donasi yang <br> terkumpul tersebut akan dibuat paket sembako yang siap <br> didistribusikan kepada masyarakat terdampak Covid-19. Dengan <br> adanya paket sembako ini diharapkan dapat meringankan <br> beban mereka para pejuang di keluarganya.</p>
            </div>
                <img class="h-auto w-[50%]" src="../assets/img/sd1.png" alt="">
            </div>
        </swiper-slide>
        <swiper-slide><div class="flex items-center justify-between px-[20px] md:px-[70px] ">
            <div class="lg:text-[13px] text-[5px] md:text-[8px]">
                <p class="text-emerald-700">CERITA CERITA SUKSES</p>
                <h1 class="lg:text-[23px] text-[10px] md:text-[17px] text-emerald-700 font-bold">Penyaliran donasi pelita Untuk <br> Negeri,Desa Ciceuri Kab. <br> Bandung Barat</h1>
                <p>Untuk itu, di bulan yang Allah turunkan keberkahan, bulan suci <br> Ramadhan, tim YABI mengerahkan para relawan YABI untuk <br> sama-sama menggalangkan donasi. Dimana donasi yang <br> terkumpul tersebut akan dibuat paket sembako yang siap <br> didistribusikan kepada masyarakat terdampak Covid-19. Dengan <br> adanya paket sembako ini diharapkan dapat meringankan <br> beban mereka para pejuang di keluarganya.</p>
            </div>
                <img class="h-auto w-[50%]" src="../assets/img/sd1.png" alt="">
            </div>
        </swiper-slide>
      
    </swiper>
  </template>
  <script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from "swiper/vue";
  
  // Import Swiper styles
  import "swiper/css";
  
//   import "swiper/css/navigation";
  
//   import "./style.css";
  
  // import required modules
  import { Navigation } from "swiper";
  
  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Navigation],
      };
    },
  };
  </script>
  