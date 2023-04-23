<template>
  <div>
    <MyEclipse class="hidden" />

    <!-- <nav class="fixed z-40 top-0 py-9 bg-transparent w-screen">
      <div class="px-16 flex items-center justify-between bg-transparent w-3/4 m-auto">
        <img src="@/assets/img/logo.svg" alt="Logo" class="w-12 bg-transparent" />

        <div class="flex items-center gap-4 bg-transparent">
          <button
            class="text-black transition-all font-medium text-sm px-5 py-2 border-2 border-black bg-light"
          >
            Acessar QR-Scan
          </button>

          <button
            class="text-black transition-all font-medium text-sm px-5 py-2 border-2 border-black bg-light"
          >
            Repositório
          </button>
        </div>
      </div>
    </nav> -->

    <header
      class="flex items-center justify-between absolute top-1/2 left-1/2 w-4/5 -translate-x-1/2 -translate-y-1/2"
    >
      <div class="flex flex-col gap-7 w-5/12">
        <h1 class="text-black font-medium text-6xl">
          Gere e escaneie QR Codes de forma fácil
        </h1>

        <p class="text-black/90 tracking-wide">
          Com o QR-Scan, você pode criar e escanear QR Codes de forma rápida e fácil.
          Use-o para gerar QR Codes para suas redes sociais favoritas, como Instagram,
          Twitter, LinkedIn, ou mesmo para seu site pessoal. Experimente agora e veja como
          é simples!
        </p>

        <div class="flex w-full items-center justify-between gap-3 mt-3">
          <button
            class="bg-light text-black font-medium tracking-wide px-6 py-3 w-full border-2 border-black"
          >
            Acessar QR-Scan
          </button>
          <button
            class="bg-light text-black font-medium tracking-wide px-6 py-3 w-full border-2 border-black"
          >
            Acessar Repositório
          </button>
        </div>
      </div>

      <MyPhones />
    </header>
  </div>
</template>

<script>
import MyEclipse from "./MyEclipse.vue";
import MyPhones from "./MyPhones.vue";
export default {
  components: { MyEclipse, MyPhones },
  name: "MyNav",
};
</script>

<style></style>
