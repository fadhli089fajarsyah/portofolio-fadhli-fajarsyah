<template >
     <div class="overflow-hidden ">
        <navbar />
        <div class="h-[42px] md:h-[40px] lg:h-[60px]"></div>
            <div class="flex h-[100px] items-center justify-center bg-progam bg-cover w-full xl:h-[300px] md:h-[200px]">
                <h1 class="xl:text-5xl md:text-2xl font-bold text-white">PROGAM KAMI</h1>
            </div>
            <h1 class="flex text-[10px] md:text-[16px] justify-center items-center font-bold text-center py-[10px] md:py-[20px] xl:text-[25px] text-indigo-900 xl:py-[70px]">Dakwah dan keumatan,sosial dan kemanusiaan menjadi pilar progam <br>
            Yayasan Abdi Bakti Izzati dalam rangka membangun dan <br> 
            memberdayakan segenap potensi masyarakat muslim indonesia
            </h1>
            <!-- pembungkus card -->
            <div class="flex flex-wrap justify-center items-center xl:">
                <!-- card -->
                <div class="xl:w-[400px] w-[100%] md:w-[300px] text-[10px] xl:text-[16px]  px-[50px]">
                    <div class="bg-blue-100 w-full p-[30px] text-center border rounded-xl border-none h-full items-center justify-center flex flex-col mb-[15px]">    
                        <img class=" w-[350px]" src="../assets/img/kk.png" alt="">
                        <a class="xl:px-[40px] px-[40px] py-[6px] mt-[-10px] md:mt-[-10px] xl:mt-[-20px] rounded font-bold text-white bg-indigo-900 md:px-[16px] md:py-[5px] xl:py-[10px] hover:bg-teal-500 hover:text-black">kemanusiaan</a>
                        <p class="font-semibold my-[10px] xl:my-[20px] md:my-[10px] " >Penaganan penyelamataan bagi masyarakat yang kecil juga warga terdampak dimasa darurat becana</p>
                        <a href="" class="text-blue-900 underline decoration-3 underline-offset-2 font-semibold hover:text-teal-500" >SELENGKAPNYA</a>
                    </div>
                </div>
                <div class="xl:w-[400px] w-[100%] md:w-[300px] text-[10px] xl:text-[16px] px-[50px] ">
                    <div class="bg-blue-100 w-full p-[30px] text-center border rounded-xl border-none h-full items-center justify-center flex flex-col mb-[15px]">
                        <img class="w-[350px]" src="../assets/img/c.png" alt="">
                        <a class="xl:px-[40px] px-[40px] py-[6px] mt-[-10px] md:mt-[-10px] xl:mt-[-20px] rounded font-bold text-white bg-indigo-900 md:px-[16px] md:py-[5px] xl:py-[10px] hover:bg-teal-500 hover:text-black">Sosial</a>
                        <p class="font-semibold my-[10px] xl:my-[20px] md:my-[10px]" >Penaganan penyelamataan bagi masyarakat yang kecil juga warga terdampak dimasa darurat becana</p>
                        <a href="" class="text-blue-900 underline decoration-3 underline-offset-2 font-semibold hover:text-teal-500" >SELENGKAPNYA</a>
                    </div>
                </div>
                <div class="xl:w-[400px] w-[100%] md:w-[300px] text-[10px] xl:text-[16px] px-[50px] ">
                    <div class="bg-blue-100 w-full p-[30px] text-center border rounded-xl border-none h-full items-center justify-center flex flex-col mb-[15px]">
                        <img class="w-[350px]" src="../assets/img/b.png" alt="">
                        <a class="xl:px-[30px] px-[40px] py-[6px] mt-[-10px] md:mt-[-10px] xl:mt-[-20px] rounded font-bold text-white bg-indigo-900 md:px-[10px] md:py-[5px] xl:py-[10px] hover:bg-teal-500 hover:text-black">Dakwah & Keumatan</a>
                        <p class="font-semibold my-[10px] xl:my-[20px] md:my-[10px]" >Dakwa dan eumatan sebagai pilar untuk memfasilitasi kegiatan dakwah dan keagamaan di masyarakat</p>
                        <a href="" class="text-blue-900 underline decoration-3 underline-offset-2 font-semibold hover:text-teal-500" >SELENGKAPNYA</a>
                    </div>
                </div>
            </div>
         <TheFooter />
    </div>
</template>

<style>
    .bg-progam{
    background-image: url("../assets/img/judul.png");
}
</style>