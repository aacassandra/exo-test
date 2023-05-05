<template>
  <LandingLayout>
    <!-- Body -->
    <MainBanner />
    <!-- Service -->
    <Services />

    <div class="w-full">
      <div class="container mx-auto px-40">
        <div class="grid grid-cols-12">
          <div
            class="my-20 col-span-12 text-center font-bold"
            style="font-size: 35px"
          >
            LATEST PRODUCTS
          </div>
        </div>
      </div>
    </div>

    <div class="w-full bg-gray-100 py-12 mt-20">
      <div class="container mx-auto px-40">
        <div class="grid grid-cols-12">
          <div class="col-span-8">
            <div style="font-size: 35px" class="font-bold">
              CV ANUGERAH PRATAMA
            </div>
            <div
              style="border-top: 3px solid black; width: 200px"
              class="my-8"
            ></div>
            <div style="font-size: 25px">About Us</div>
            <div style="font-size: 18px" class="mt-4">
              CV Anugerah Pratama adalah perusahaan yang berdiri sejak 1
              September 2018 dan bergerak di bidang distribusi dan manufaktur
              lampu khususnya yang berbasis LED ( Light Emitting Diode ).
            </div>
            <p style="font-size: 14px" class="mt-4">
              Seiring dengan perkembangan teknologi dan inovasi dalam industri
              penerangan dunia, kami ingin menawarkan solusi untuk kebutuhan
              lampu indoor dan outdoor di Indonesia untuk menggantikan lampu
              yang lebih konvensional seperti CFL, Merkurius, Halogen, atau
              jenis pencahayaan lainnya.
            </p>
            <button
              class="bg-black px-3 py-1 text-white hover:bg-gray-800 mt-4 transition-all duration-200"
            >
              View More
            </button>
          </div>
        </div>
      </div>
    </div>
  </LandingLayout>
</template>
<script setup>
  import LandingLayout from '@/Layouts/LandingLayout.vue'
  import MainBanner from '@/Components/atoms/MainBanner.vue'
  import Services from '@/Components/atoms/Services.vue'
</script>
