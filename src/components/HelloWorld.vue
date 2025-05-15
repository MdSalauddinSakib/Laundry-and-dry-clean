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

  <section class="px-20">
    <nav class="bg-gray-800 p-4">
      <div class="container mx-auto flex justify-between items-center">
        <a href="#" class="text-white text-xl font-bold">Logo</a>
        <div class="hidden md:flex space-x-4">
          <a href="#" class="text-white hover:text-gray-300">Home</a>
          <a href="#" class="text-white hover:text-gray-300">About</a>
          <a href="#" class="text-white hover:text-gray-300">Contact</a>
        </div>
        <button class="md:hidden text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
          </svg>
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
