<template>
  <main class="op-hero md:pt-[160px] pt-[115px] -mt-[80px]">
    <div class="max-w-[1200px] mx-auto xl:px-[10px] lg:px-[60px] sm:px-[80px] ">
      <div class="w-full grid md:grid-cols-2">
       <div class="lg:text-left text-center px-[20px]">
        <h2 class="font-[800] lg:text-[60px] text-[30px] text-[#fff] mb-[24px]">
          Thriving in the Digital Landscape Made Easy
        </h2>
        <p
          class="font-[400] lg:text-[28px] text-[20px] text-[#fff] leading-[-1.4px]"
        >
          Leverage our Exceptional Services to boost your Online Business
          growth.
        </p>
        <button class="md:mt-[48px] mt-[32px] mb-[50px] rounded-full md:px-[60px] px-[40px] md:py-[22px] py-[18px] bg-[#2C093C] text-[20px] text-[#fff]">
          Get Started
        </button>
       </div>
        <div class="md:order-2 order-1">
          <img class="w-full" src="/images/hero_img_2.png" alt="hero-img-2" />
        </div>
      </div>
    </div>
  </main>
</template>

<script setup></script>

<style scoped>
.op-hero {
  background: url("/icons/hero-bg-2.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  min-height: 100vh;
  height: 100%;
}
</style>
