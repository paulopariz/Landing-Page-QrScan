<template>
  <div class="w-full h-screen p-20 bg-black mt-96 m-auto">
    <div class="flex items-start justify-between w-3/4 m-auto">
      <img src="@/assets/img/Untitled2.png" class="w-96" alt="Phone History" />

      <div class="flex justify-end w-1/2">
        <div class="flex flex-col gap-6">
          <h1 class="text-4xl font-medium text-white leading-snug">
            <span class="bg-light text-black px-0.5">Gerencie</span> seu histórico "Scan"
            e "Gerados"
          </h1>
          <p class="text-white-2 leading-8">
            Todos os QR Codes que você gerar ficarão registrados no histórico "Gerados",
            enquanto os que você escanear serão armazenados no histórico "Scan". Através
            desses históricos, você poderá gerenciá-los de forma fácil e prática. Além
            disso, é possível fazer o download tanto dos QR Codes escaneados quanto dos
            gerados. O objetivo do histórico é garantir que nenhum QR Code seja perdido e
            que fique armazenado de forma segura. Caso você deseje excluir algum QR Code,
            é possível apagar um por vez ou, se preferir, deletar todos de uma vez só.
          </p>

          <div class="h-[0.2px] bg-white-2/10 w-full mt-12"></div>

          <div class="w-full mt-12 flex items-center justify-start gap-14">
            <div v-for="item in sectionHistory" :key="item.id">
              <div class="flex flex-col items-start gap-3 w-56">
                <img :src="item.icon" alt="Icon Bin" />
                <h1 class="text-xl font-semibold">{{ item.title }}</h1>
                <p class="text-sm text-white-2">
                  {{ item.desc }}
                </p>
              </div>
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
