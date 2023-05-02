<template>
  <div
    class="w-9/12 h-[500px] bg-light p-16 px-32 m-auto overflow-hidden -mt-[250px] flex justify-between items-center"
  >
    <div class="flex flex-col gap-8 w-2/5 z-40">
      <div>
        <h1 class="text-black text-5xl font-semibold leading-tight">
          Teste agora mesmo!
        </h1>
        <p class="text-black">
          Não espere mais. Aproveite ao máximo todos os recursos disponíveis através do
          QR-Scan!
        </p>
      </div>
      <button
        class="px-4 py-5 flex items-center gap-3 justify-center w-1/2 uppercase bg-black font-semibold transition-all hover:scale-95"
      >
        QR-SCAN
        <img src="@/assets/img/iconArrrow.svg" alt="Icon Arrow" class="w-6" />
      </button>
    </div>
    <div>
      <img src="@/assets/img/PhoneEnter.png" alt="Phone" class="w-96 mt-72" />
    </div>
  </div>
</template>

<script>
export default { components: {} };
</script>

<style></style>
