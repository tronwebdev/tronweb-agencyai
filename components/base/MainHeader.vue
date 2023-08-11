<template>
   <header
    :class="{ 'shadow-md': isScrolled }"
    class="sticky top-0 w-full py-4 bg-white z-10 lg:px-[80px] px-[16px]"
  >
    <div class="max-w-[1200px] mx-auto w-full flex items-center justify-between">
      <div>
        <img src="/icons/logo.svg" alt="agency_ai_logo">
      </div>
      <nav>
        <ul class="flex items-center lg:space-x-8 space-x-4">
          <a href="#"><li class="border-b-2 border-transparent hover:border-b-2 hover:border-[#AB3ADD] hover:text-[#AB3ADD] transition duration-300">Products</li></a>
          <a href="#"><li class="border-b-2 border-transparent hover:border-b-2 hover:border-[#AB3ADD] hover:text-[#AB3ADD] transition duration-300">Features</li></a>
          <a href="#"><li class="border-b-2 border-transparent hover:border-b-2 hover:border-[#AB3ADD] hover:text-[#AB3ADD] transition duration-300">How It Works</li></a>
          <a href="#"><li class="border-b-2 border-transparent hover:border-b-2 hover:border-[#AB3ADD] hover:text-[#AB3ADD] transition duration-300">Tools</li></a>
        </ul>
      </nav>
      <a href="#">
        <button class="bg-[#AB3ADD] rounded-full text-white px-4 py-3">Affiliate Link</button>
      </a>
    </div>
  </header>
</template>



<script setup>
import { ref, onMounted } from 'vue';

const isScrolled = ref(false);

onMounted(() => {
  window.addEventListener('scroll', handleScroll);
});

const handleScroll = () => {
  isScrolled.value = window.scrollY > 50;
};
</script>

<style>
/* Add other styles as needed */
</style>