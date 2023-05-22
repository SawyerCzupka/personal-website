<template>
  <div class="grid grid-flow-col gap-10 place-items-center w-[700px]">
    <!-- Picture -->

    <div class="relative w-64 h-64 rounded-full overflow-hidden">
      <img
        class="absolute scale-[1.8] w-full top-24"
        src="img/DSC_9117.jpg"
        alt=""
      />
    </div>

    <div class="flex flex-col font-wix">
      <p
        class="text-center text-5xl font-semibold text-white underline decoration-rose-500 underline-offset-[14px]"
      >
        Sawyer Czupka
      </p>

      <!-- Title -->
      <p class="pt-5 text-lg text-white font-medium">
        Aspiring <span class="">Machine Learning Engineer</span>
      </p>

      <p class="pt-5 text-lg text-white font-medium">
        Email: sawyerczupka@gmail.com
      </p>

      <p class="text-lg text-white font-medium">Phone: (757) 818-0742</p>
    </div>
    <!-- Name -->
  </div>
</template>

<style>
  .text-outline {
    text-shadow: 1px 2px 0px theme("colors.rose.500");
  }
</style>
