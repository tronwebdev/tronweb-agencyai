<template>
  <main>
    <OtherpagesHero2 />
    <main class="lg::mt-[-80px] md:mt-[-200px] mt-[-100px]">
      <div class="flex md:flex-row flex-col-reverse md:items-end items-center lg:w-[80%] md:w-[95%]">
        <div class="lg:mr-[34px] md:mr-[16px] mr-[0] mb-[40px]">
            <img class="" src="/icons/consult_phot_n_bg.svg" alt="photo" />
        </div>
        <div class="bg-[#F9FAFF] md:rounded-[40px] rounded-[20px] lg:px-[40px] md:px-[24px] px-[16px] lg:py-[50px] md:py-[24px] py-[20px] md:w-[60%] w-[90%] mx-auto">
          <h3 class="lg:text-[60px] md:text-[40px] text-[30px] text-[#232323] font-[700] md:leading-[72px]">
            Get Free Consultation
          </h3>
          <p class="md:text-[18px] text-[16px] text-[#232323]">Fill out your details Below to get a free Consultation.</p>
          <form class="lg:mt-[50px] md:mt-[40px] mt-[24px]">
            <input class="px-[24px] py-[20px] w-full border rounded-[100px] border-[#DCDCDC] bg-transparent lg:mb-[30px] md:mb-[24px] mb-[20px]" type="text" name="name" placeholder="Full Name">
            <input class="px-[24px] py-[20px] w-full border rounded-[100px] border-[#DCDCDC] bg-transparent md:mb-[40px] mb-[25px]" type="email" name="email" placeholder="Email Address">
            <button class="w-full bg-[#AB3ADD] md:py-[21px] py-[16px] md:px-[32px] px-[20px] md:text-[20px] text-[16px] text-[#fff] rounded-[100px]">
                Get Started
            </button>
          </form>
        </div>
      </div>
    </main>
    <OtherpagesHelpyou />
    <OtherpagesReviews/>
    <BaseMainFooter />
  </main>
</template>

<script setup lang="ts"></script>

<style></style>
