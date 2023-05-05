<template>
  <div class="grid grid-cols-12 mt-10">
    <div class="col-span-6">
      <img src="/images/Logo.png" alt="" style="width: 270px; height: 60px" />
    </div>
    <div class="col-span-6 flex justify-end items-center">
      <div class="flex items-center">
        <input
          type="text"
          placeholder="Type here"
          class="outline-none ring-0 focus:outline-none focus:border-gray-400 focus:ring-0 border-gray-400"
          style="height: 40px"
        />
        <div>
          <div style="margin-left: -30px">
            <i class="fas fa-search"></i>
          </div>
        </div>
      </div>
      <div class="ml-6">
        <i
          class="fas fa-user cursor-pointer text-gray-300 hover:text-black"
        ></i>
      </div>
      <div class="mx-6">
        <i
          class="fas fa-bag-shopping cursor-pointer text-gray-300 hover:text-black"
        ></i>
      </div>
    </div>
  </div>
  <div class="grid grid-cols-12 mt-10">
    <div class="col-span-12 flex items-center">
      <div class="text-gray-400 cursor-pointer hover:text-black text-xl mr-6">
        <ResponsiveNavLink
          :href="route('home')"
          :active="route().current('home')"
          in-class-active="text-black cursor-pointer hover:text-black text-xl"
          in-class-in-active="text-gray-400 cursor-pointer hover:text-black text-xl"
        >
          Home
        </ResponsiveNavLink>
      </div>
      <div class="text-gray-400 cursor-pointer hover:text-black text-xl mr-6">
        Products
      </div>
      <div class="text-gray-400 cursor-pointer hover:text-black text-xl mr-6">
        <ResponsiveNavLink
          :href="route('about')"
          :active="route().current('about')"
          in-class-active="text-black cursor-pointer hover:text-black text-xl"
          in-class-in-active="text-gray-400 cursor-pointer hover:text-black text-xl"
        >
          About
        </ResponsiveNavLink>
      </div>
      <div class="text-gray-400 cursor-pointer hover:text-black text-xl mr-6">
        <ResponsiveNavLink
          :href="route('contact')"
          :active="route().current('contact')"
          in-class-active="text-black cursor-pointer hover:text-black text-xl"
          in-class-in-active="text-gray-400 cursor-pointer hover:text-black text-xl"
        >
          Contact
        </ResponsiveNavLink>
      </div>
    </div>
  </div>
</template>
<script setup>
  import ResponsiveNavLink from '@/Components/ResponsiveNavLink.vue'
</script>
