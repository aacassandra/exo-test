<template>
  <div class="w-full mb-5">
    <div class="container mx-auto px-40">
      <Header />
    </div>
  </div>
  <slot />
</template>

<script setup>
  import Header from '@/Components/molecules/Header.vue'
</script>
