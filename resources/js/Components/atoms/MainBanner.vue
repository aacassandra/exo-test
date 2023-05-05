<template>
  <div class="glide">
    <div class="glide__track" data-glide-el="track">
      <ul class="glide__slides">
        <li class="glide__slide">
          <img
            src="/images/banners/main/bg-5.jpg"
            alt=""
            style="width: 100%; height: 572px; object-fit: cover"
          />
        </li>
        <li class="glide__slide">
          <img
            src="/images/banners/main/platinumwp-1.jpg"
            alt=""
            style="width: 100%; height: 572px; object-fit: cover"
          />
        </li>
      </ul>
    </div>
  </div>
</template>
<script setup>
  import { onMounted } from 'vue'
  import Glide from '@glidejs/glide'
  import '@glidejs/glide/dist/css/glide.core.min.css'

  onMounted(() => {
    new Glide('.glide').mount()
  })
</script>
