<template>
    <div class="overflow-hidden">
        <navbar />
        <div class="h-[42px] md:h-[40px] lg:h-[60px]"></div>
            <!-- isi1 -->
            <div class="flex text- center flex-col h-[100px] items-center justify-center bg-dn bg-cover w-full lg:h-[300px] md:h-[200px]">
                <h1 class="lg:text-[25px] text-[7px] md:text-[15px] font-bold">H.R Imam an Nasa-i, Ibnu Khuzaimah dan Ibnu Hibban dalam shahihnya</h1>
                <p class="lg:text-[13px] text-[5px] md:text-[8px] py-[5px] pb-[8px]">Satu dirham mengungguli seratus dirham. Seorang bertanya:</p>
                <p class="lg:text-[13px] text-[5px] md:text-[8px] text-center ">"Bagaimana itu wahai Rasulullah?" Beliau menjawab: Seseorang mempunyai harta yang melimpah lalu dia mengambil <br> dari kantongnya seratus ribu dirham dan menyedekahkannya. Dan seorang yang lain hanya memiliki dua dirham, dia <br> mengambil satu dirham lalu mensedekahkannya.</p>
            </div>
            <!-- akhir 1 -->
            <!-- isi2 -->
            <h1 class="flex justify-center items-center font-bold text-blue-900 md:text-[20px] lg:text-[30px] py-[20px]">DONASI</h1>
            <div class="md:flex md:mb-[30px]">
                <div class="md:w-[50%] flex items-center justify-center">
                    <img class="hidden md:flex md:w-[300px] lg:w-[500px]" src="../assets/img/ad.png" alt="">
                    <img class="h-auto w-[80%] md:z-10 md:ml-[-280px] md:mt-[-50px] lg:ml-[-450px] xl:w-[70%]"  src="../assets/img/ae.png" alt="">
                </div>

                <from class="md:w-[50%] flex flex-col text-[6px] px-[40px] py-[10px] md:text-[12px] lg:text-[17px] justify-center">
                    <label class="font-medium" for="sapaan">Sapaan</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[4px]" type="text" id="sapaan" name="sapaan">
                    
                    <label class="font-medium" for="nama">Nama Lengkap</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[4px]" type="text" id="nama" name="nama">
                    
                    <label class="font-medium" for="alamat">Alamat</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[20px] py-[10px]" type="text" id="alamat" name="alamat">
                    
                    <label class="font-medium" for="email">Email</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[4px]" type="text" id="email" name="email">
                    
                    <label class="font-medium" for="telepon">Telepon/HP</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[4px]" type="text" id="telepon" name="telepon">
                    
                    <label class="font-medium" for="jenis donasi">Jenis Donasi</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[4px]" type="text" id="jenis donasi" name="jenis donasi">
                    
                    <label class="font-medium" for="jumlah-rp">Jumlah (Rp)</label>
                    <input class="mb-[5px] py-[5px] lg:mb-[20px] border-black border-[0.1px] border md:rounded md:py-[4px]" type="text" id="jumlah-rp" name="jumlah-rp">
                   
                    <button class="h-auto w-[120px] md:w-[200px] lg:w-[380px]"><img src="../assets/img/ddn].png" alt=""></button>
                    <button class="bg-blue-900 text-white py-[10px] rounded font-bold">Donasi</button>
                </from>
            </div>
            <!-- qlhir 2 -->

        <TheFooter />
    </div>
</template>

<style>
    .bg-dn{
        background-image: url(../assets/img/bgdn.png);
    }
</style>