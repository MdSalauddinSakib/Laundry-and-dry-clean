<script setup>

</script>

<template>
  <!-- top bar -->
  <section class="bg-[#4375E7] px-20 font-poppins">
    <!-- top bar left element -->
    <div class="container mx-auto text-white flex justify-between text-base">
      <div class="flex flex-row items-center gap-4 py-3">
        <p>Follow Us:</p>
        <i class="text-[#a1baf3] hover:text-white cursor-pointer fa-brands fa-facebook-f"></i>
        <i class="text-[#a1baf3] hover:text-white cursor-pointer fa-brands fa-linkedin-in"></i>
        <i class="text-[#a1baf3] hover:text-white cursor-pointer fa-brands fa-twitter"></i>
        <i class="text-[#a1baf3] hover:text-white cursor-pointer fa-brands fa-pinterest"></i>
      </div>

      <!-- top bar right element -->
      <div class="flex flex-row items-center gap-4">
        <p><i class="fa-solid fa-location-dot"></i>&nbsp; <span class="text-[#ffffffb3]"> Holland, London 7QU UK</span>
        </p>
        <div class="h-5 w-px bg-[#ffffff52]"></div>
        <p><i class="fa-solid fa-phone"></i> <span class="text-[#ffffffb3]"> &nbsp;(234) 987 - 354 - 3670</span></p>
        <div class="h-5 w-px bg-[#ffffff52]"></div>
        <p><i class="fa-solid fa-envelope"></i> &nbsp;<span class="text-[#ffffffb3]"> Email: example@gmail.com</span>
        </p>
      </div>
    </div>
  </section>
  <!-- top bar end -->

  <!-- nav bar -->
  <section class="px-20">
    <nav class="p-4">
      <div class="container mx-auto flex justify-between items-center font-medium text-base text-[#142137]">
        <!-- logo -->
        <a href="#" class="text-3xl font-bold flex items-center"><img src="../assets/img/logo.png" alt="">&nbsp;Laundry</a>
        <!-- menu -->
        <div class="hidden md:flex space-x-4">
          <a href="#" class=" hover:text-[#4375E7]">Home <i class="fa-solid fa-angle-down"></i></a>
          <a href="#" class=" hover:text-[#4375E7]">About Us</a>
          <a href="#" class=" hover:text-[#4375E7]">Service <i class="fa-solid fa-angle-down"></i></a>
          <a href="#" class=" hover:text-[#4375E7]">Pages <i class="fa-solid fa-angle-down"></i></a>
          <a href="#" class=" hover:text-[#4375E7]">Blog <i class="fa-solid fa-angle-down"></i></a>
          <a href="#" class=" hover:text-[#4375E7]">Contact</a>
        </div>
        <button class="cursor-pointer p-4 border border-[#14213733]">
          Schedule a Pickup <i class="fa-solid fa-arrow-right"></i>
        </button>
      </div>
    </nav>
  </section>

  <section class="px-20">
    <div class="max-w-sm rounded-lg overflow-hidden shadow-lg bg-white">
      <img class="w-full h-48 object-cover" src="../assets/img/logo.png" alt="Card Image">
      <div class="px-6 py-4">
        <h2 class="font-bold text-xl mb-2">Card Title</h2>
        <p class="text-gray-700 text-base">
          This is a sample card component built with Tailwind CSS.
        </p>
      </div>
      <div class="px-6 pt-4 pb-2">
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#tag1</span>
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#tag2</span>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>
