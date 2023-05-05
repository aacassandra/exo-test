<template>
  <LandingLayout>
    <div class="w-full bg-black">
      <div class="container mx-auto px-40">
        <div class="grid grid-cols-12">
          <div
            class="my-20 col-span-12 font-bold text-white"
            style="font-size: 35px"
          >
            CONTACT US
          </div>
        </div>
      </div>
    </div>

    <div class="w-full">
      <div class="container mx-auto px-40">
        <div class="grid grid-cols-12">
          <div class="col-span-6 my-10" style="font-size: 25px">
            Leave a message
          </div>
          <div class="col-span-6 my-10 pl-10" style="font-size: 25px">
            Contact Info
          </div>
          <div class="col-span-6">
            <div class="grid grid-cols-12">
              <div class="col-span-6 pr-2">
                <div class="form-control w-full max-w-xs">
                  <label class="label">
                    <span class="label-text font-bold">Name</span>
                  </label>
                  <input
                    type="text"
                    class="input input-bordered w-full max-w-xs"
                  />
                </div>
              </div>
              <div class="col-span-6">
                <div class="form-control w-full max-w-xs">
                  <label class="label">
                    <span class="label-text font-bold">Email</span>
                  </label>
                  <input
                    type="email"
                    class="input input-bordered w-full max-w-xs"
                  />
                </div>
              </div>
              <div class="col-span-12 mt-4">
                <div class="form-control w-full">
                  <label class="label">
                    <span class="label-text font-bold">Feedback</span>
                  </label>
                  <textarea
                    class="textarea textarea-bordered w-full"
                    placeholder=""
                  ></textarea>
                </div>
                <button
                  class="bg-black px-3 py-1 text-white hover:bg-gray-800 mt-4 transition-all duration-200"
                >
                  Submit
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </LandingLayout>
</template>
<script setup>
  import LandingLayout from '@/Layouts/LandingLayout.vue'
</script>
