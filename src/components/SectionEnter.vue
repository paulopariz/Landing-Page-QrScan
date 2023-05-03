<template>
  <div
    class="w-9/12 h-[500px] bg-light m-auto overflow-hidden -mt-[250px] flex justify-between items-center max-lg:h-[730px] max-lg:flex-col max-lg:-mt-[330px] max-sm:w-full max-xl:w-5/6 max-sm:h-[690px] max-mn:h-[650px]"
  >
    <img
      src="@/assets/img/Eclipse.svg"
      alt="Eclipse"
      class="absolute w-52 h-52 -mt-52 ml-24 max-lg:mt-0 max-lg:-ml-52 max-sm:w-36 max-sm:h-36 max-sm:-ml-32"
    />
    <img
      src="@/assets/img/Eclipse.svg"
      alt="Eclipse"
      class="absolute ml-[600px] mt-40 h-52 w-52 rotate-90 max-2xl:ml-[450px] max-xl:ml-[400px] max-md:w-32 max-md:h-32 max-md:ml-64 max-sm:h-24 max-sm:w-24 max-sm:ml-44"
    />

    <div
      class="flex flex-col justify-center gap-8 w-7/12 h- z-40 max-lg:w-full max-lg:items-center max-md:gap-4 bg-light/10 backdrop-blur-md py-10 px-12 max-sm:px-6 max-sm:py-8"
    >
      <div class="flex flex-col gap-2">
        <h1
          class="text-black text-5xl font-semibold leading-[3.3rem] max-lg:text-center max-md:text-4xl max-sm:text-3xl"
        >
          Teste agora mesmo!
        </h1>
        <p
          class="text-black w-3/4 max-xl:w-4/5 max-lg:w-full max-lg:text-center max-sm:text-sm"
        >
          Não espere mais. Aproveite ao máximo todos os recursos disponíveis através do
          QR-Scan!
        </p>
      </div>

      <button
        class="py-4 flex items-center gap-3 bg-black justify-center w-56 uppercase font-medium transition-all max-xl:py-4 max-xl:w-52 rounded-md overflow-hidden max-sm:py-2.5 max-sm:w-44"
      >
        <span class="transition-all delay-150 max-sm:text-xs">QR-SCAN</span>
        <img
          src="@/assets/img/iconArrrow.svg"
          alt="Icon Arrow"
          class="w-6 -rotate-45 transition-all delay-150 max-sm:w-5"
        />
      </button>
    </div>
    <div class="py-16 px-12 z-40 max-sm:px-6 max-sm:py-8">
      <img src="@/assets/img/PhoneEnter.png" alt="Phone" class="w-96 mt-72 max-lg:mt-5" />
    </div>
  </div>
</template>

<script>
export default { components: {} };
</script>

<style lang="scss" scoped>
button:hover {
  span {
    animation-delay: 1s;
    display: none;
  }
  img {
    rotate: 45deg;
  }
}
</style>
