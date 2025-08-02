<script setup>
import bg from '@/assets/img/herosection.png'
</script>

<template>
  <div
    :style="`background-image: url(${bg}); background-size: cover; background-position: center;`"
    class="w-full md:h-[849px] h-auto flex justify-center items-center mb-6 p-3"
  >
    <div class="max-w-screen-xl mx-auto">
      <h1 class="text-[#FFBE38] text-[36px] md:text-[65px] font-semibold max-w-[658px]">
        Build Wealth with Crypto
      </h1>
      <p class="text-[#E0E0E0] font-normal text-lg max-w-[740px] mb-[73px]">
        Join the growing community on Zaptrade — the trusted destination for effortless crypto
        investing and trading.
      </p>
      <div class="md:flex block gap-4 items-center">
        <div
          class="bg-[#1E2329] min-h-16 p-2 rounded-md gap-2 flex border border-[#4A4A4A] w-full max-w-[492px]"
        >
          <input
            type="text"
            class="w-full h-auto bg-transparent text-white border-none outline-none pl-2"
            placeholder="Email/Phone number"
          />
          <button
            class="bg-[#FFBE38] text-[#1C1C1E] font-semibold px-6 py-2 rounded-md whitespace-nowrap"
          >
            Sign Up
          </button>
        </div>

        <p class="text-[#E0E0E040] text-center my-4">or</p>

        <div
          class="bg-[#1E2329] h-16 p-4 rounded-md justify-center items-center gap-4 flex border border-[#4A4A4A]"
        >
          <button>
            <img src="../assets/img/google.svg" alt="" />
          </button>
          <button>
            <img src="../assets/img/apple.svg" alt="" />
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
