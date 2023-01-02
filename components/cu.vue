<template>
    <swiper
      :spaceBetween="30"
      :centeredSlides="true"
      :autoplay="{
        delay: 2500,
        disableOnInteraction: false,
      }"
      :pagination="{
        clickable: true,
      }"
      :navigation="true"
      :modules="modules"
      class="mySwiper "
    >
      <swiper-slide ><img class="w-[100%]" src="../assets/img/nb.png" alt=""></swiper-slide>
      <swiper-slide ><img class="w-[100%]" src="../assets/img/nb.png" alt=""></swiper-slide>
      <swiper-slide ><img class="w-[100%]" src="../assets/img/nb.png" alt=""></swiper-slide>
    </swiper>
  </template>
  <script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from "swiper/vue";
  
  // Import Swiper styles
  import "swiper/css";
  
  import "swiper/css/pagination";
//   import "swiper/css/navigation";
  
//   import "./style.css";
  
  // import required modules
  import { Autoplay, Pagination, Navigation } from "swiper";
  
  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Autoplay, Pagination, Navigation],
      };
    },
  };
  </script>

<style>
.swiper-button-prev{
    opacity: 0;
}
.swiper-button-disabled{
    opacity: 0;
}
.swiper-button-next{
    opacity: 0;
}
</style>