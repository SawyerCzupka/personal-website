<template class="nuxt-scrollbars">
  <!-- https://mckvr.com/ -->
  <main class="bg-neutral-800">
    <section class="pattern h-screen w-screen flex justify-center items-start">
      <!-- Card -->
      <div
        class="flex flex-col justify-center items card border-gray-400 border-2 mt-40"
      >
        <Profile class="outline-red-400" />
        <Contact class="pt-10" />
      </div>
    </section>
  </main>
</template>

<style>
  .background {
    background-color: rgba(29, 30, 33);
  }

  ::-webkit-scrollbar {
    background-color: transparent;
    height: 0.2em;
    width: 0.5em;
  }

  ::-webkit-scrollbar-track {
    --tw-bg-opacity: 1;
    background-color: #27272a;
    background-color: rgb(39 39 42 / var(--tw-bg-opacity));
  }

  ::-webkit-scrollbar-thumb {
    --tw-bg-opacity: 1;
    background-color: #3f3f46;
    background-color: rgb(63 63 70 / var(--tw-bg-opacity));
    border-radius: 0.6em;
  }

  .pattern {
    background: transparent;
    background-image: radial-gradient(
      theme("colors.rose.500") 1px,
      transparent 1px
    );
    background-size: 50px 50px;
  }

  .card {
    width: 800px;
    padding: 2.5rem;
    background-color: rgba(29, 30, 33);
    border-radius: 30px;
  }
</style>
