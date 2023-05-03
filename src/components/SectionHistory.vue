<template>
  <div
    class="w-full p-20 pb-96 max-lg:pb-[450px] bg-black mt-36 m-auto flex items-center justify-between max-lg:flex-col max-lg:items-center max-lg:gap-10 max-xl:px-12 max-md:px-8"
  >
    <img
      src="@/assets/img/PhoneHistory.png"
      class="w-96 max-lg:w-80 max-sm:w-72"
      alt="Phone History"
    />

    <div
      class="flex justify-end w-1/2 max-lg:justify-center max-lg:w-full"
      data-aos="fade-up"
    >
      <div class="flex flex-col gap-6">
        <h1
          class="text-4xl font-medium text-white leading-4 max-sm:text-3xl max-mn:text-2xl"
        >
          <span class="bg-light text-black px-0.5 leading-relaxed">Gerencie</span> seu
          histórico "Scan" e "Gerados"
        </h1>
        <p
          class="text-white-2 leading-8 max-lg:leading-7 max-sm:text-sm max-mn:text-xs max-mn:leading-5"
        >
          Todos os QR Codes que você gerar ficarão registrados no histórico "Gerados",
          enquanto os que você escanear serão armazenados no histórico "Scan". Através
          desses históricos, você poderá gerenciá-los de forma fácil e prática. Além
          disso, é possível fazer o download tanto dos QR Codes escaneados quanto dos
          gerados. O objetivo do histórico é garantir que nenhum QR Code seja perdido e
          que fique armazenado de forma segura. Caso você deseje excluir algum QR Code, é
          possível apagar um por vez ou, se preferir, deletar todos de uma vez só.
        </p>

        <div class="h-[0.2px] bg-white/10 w-full mt-12 max-lg:mt-5"></div>

        <div
          class="w-full mt-12 flex items-center justify-start gap-14 max-lg:mt-5 max-sm:flex-col max-sm:items-start max-sm:gap-8"
        >
          <div v-for="item in sectionHistory" :key="item.id">
            <div class="flex flex-col items-start gap-3 w-56 max-sm:w-full">
              <img :src="item.icon" alt="Icon Bin" />
              <h1 class="text-xl font-semibold text-white">{{ item.title }}</h1>
              <p class="text-sm text-white-2">
                {{ item.desc }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionHistory",
  components: {},

  data() {
    return {
      sectionHistory: [
        {
          icon: require("@/assets/img/iconDownload.svg"),
          title: "Download",
          desc: "No histórico, ainda é possível baixar o QR Code.",
        },
        {
          icon: require("@/assets/img/iconFilter.svg"),
          title: "Filtrar",
          desc: "Filtre pelos os mais recentes e antigos.",
        },
      ],
    };
  },
};
</script>

<style></style>
