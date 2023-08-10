<template>
  <div class="d-container w-full bg-[#fff]">
    <div class="pt-[75px] pb-[158px] w-full">
      <SharedLaunchingInfo />
      <article class="a-box md:px-[55px] px-[20px] py-[38px] mb-[27px]">
        <div
          class="w-full flex md:flex-row flex-col items-center justify-center"
        >
          <img
            class="md:mr-[60px]"
            src="/images/high-conveting-text.png"
            alt="text image"
          />
          <div
            class="md:my-0 my-[50px] bg-[#FF6FED] p-[14px] rounded-full text-[#8D00C9] text-[28px] font-[500] flex items-center justify-center"
          >
            &
          </div>
          <img
            class="md:ml-[60px]"
            src="/images/cahp-t.png"
            alt="cash prize text"
          />
        </div>
      </article>

      <SharedTicketForm />
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.a-box {
  border-radius: 24px;
  background: #8a00c7;
  box-shadow: 8px 8px 64px 0px rgba(171, 58, 221, 0.2);
  height: auto;
}
</style>
