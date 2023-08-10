<template>
  <div class="d-container w-full bg-[#fff]">
    <div class="pt-[75px] pb-[158px] w-full">
      <article class="a-box md:px-[60px] px-[20px] md:py-[38px] py-[30px] mb-[27px]">
        <div class="w-full flex items-center justify-between">
          <img
            class="md:mr-[30px] mr-[10px]"
            src="/images/launch-icon.png"
            alt="launch-icon"
          />
          <div class="w-full flex md:flex-row flex-col items-center justify-between">
            <p>
              <span class="uppercase md:text-[24px] text-[18px] text-[#E8B5FF] font-[500]"
                >Launching On</span
              >
              <br /><br />
              <span class="text-[#fff] md:text-[36px] text-[24px] font-[700]"
                >24th August 2023</span
              >
            </p>
            <img class="md:mt-[0] mt-[20px]" src="/images/e11am-etny.png" alt="launch-time" />
          </div>
        </div>
      </article>

      <article class="a-box md:px-[55px] px-[20px] py-[38px]  mb-[27px]">
        <div class="w-full flex md:flex-row flex-col items-center justify-center">
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

      <article class="b-box md:pt-[62px] pt-[40px] md:pb-[52px] pb-[30px]">
        <div class="flex flex-col items-center justify-center">
          <p class="text-center flex items-center justify-center">
            <span>Get Your</span>
            <img class="mx-[5px]" src="/images/nzoo.png" alt="nzoo" />
            <span>Affiliate Links</span>
          </p>
          <form class="my-[32px] md:mx-[0] mx-[16px] flex items-center justify-center">
            <div class="bg-[#fff] rounded-full pl-[20px] flex items-center">
              <img class="mr-[10px]" src="/icons/mail.svg" alt="mail icon" />
              <input type="text" class="bg-transparent" />
              <button type="submit" class="purple-bg-btn md:text-[18px] text-[14px] text-[#fff] md:px-[20px] px-[14px] md:py-[14px] py-[10px] self-end">
                Get Affilliate Link
              </button>
            </div>
          </form>
          <button class="yellow-bg-btn md:text-[24px] text-[18px] flex items-center">
            <img
              class="mr-[10px]"
              src="/icons/download.svg"
              alt="download icon"
            />
            Grab Your Promo Tools
          </button>
        </div>
      </article>
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
.yellow-bg-btn {
  border-radius: 74px;
  background: #ffbb38;
  box-shadow: 0px 16px 80px 0px rgba(255, 194, 54, 0.6);
  color: #201f20;
  padding: 14px 24px;
}
.b-box {
  border-radius: 24px;
  background: #e3e7fe;
}
.purple-bg-btn {
  border-radius: 132.338px;
  background: #ab3add;
}
</style>
