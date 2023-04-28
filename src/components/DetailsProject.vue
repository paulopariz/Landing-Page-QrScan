<template>
  <div class="w-full h-full bg-black py-24 mt-96">
    <div class="w-11/12 m-auto">
      <h1 class="text-5xl font-bold text-white">
        Descubra mais detalhes sobre o projeto
      </h1>

      <section class="mt-28">
        <div class="flex items-center justify-between gap-5">
          <div
            class="h-[500px] flex flex-col justify-between p-14 w-1/3 border border-light border-y-0 border-l-0 transition-all hover:bg-light"
          >
            <h1 class="text-3xl text-white font-medium tracking-wide">
              Histórico de Qrcodes
            </h1>
            <p>
              Com o QR-Scan, você tem acesso ao histórico de todos os QR Codes que foram
              gerados e escaneados, para que não perca nenhum deles e possa acessá-los
              sempre que quiser. Se preferir, também é possível excluí-los.
            </p>
          </div>
          <div
            class="h-[500px] flex flex-col justify-between p-14 w-1/3 border border-light border-y-0 border-l-0 transition-all hover:bg-light"
          >
            <h1 class="text-3xl text-white font-medium tracking-wide">
              Histórico de Qrcodes
            </h1>
            <p>
              Com o QR-Scan, você tem acesso ao histórico de todos os QR Codes que foram
              gerados e escaneados, para que não perca nenhum deles e possa acessá-los
              sempre que quiser. Se preferir, também é possível excluí-los.
            </p>
          </div>
          <div class="h-[500px] flex flex-col justify-between p-14 w-1/3">
            <h1 class="text-3xl text-white font-medium tracking-wide">
              Histórico de Qrcodes
            </h1>
            <p>
              Com o QR-Scan, você tem acesso ao histórico de todos os QR Codes que foram
              gerados e escaneados, para que não perca nenhum deles e possa acessá-los
              sempre que quiser. Se preferir, também é possível excluí-los.
            </p>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutProject",

  data() {
    return {
      details: [
        {
          title: "Histórico de Qrcodes",
          desc:
            "Com o QR-Scan, você tem acesso ao histórico de todos os QR Codes que foram gerados e escaneados, para que não perca nenhum deles e possa acessá-los sempre que quiser. Se preferir, também é possível excluí-los.",
        },
        {
          title: "Histórico de Qrcodes",
          desc:
            "Com o QR-Scan, você tem acesso ao histórico de todos os QR Codes que foram gerados e escaneados, para que não perca nenhum deles e possa acessá-los sempre que quiser. Se preferir, também é possível excluí-los.",
        },
        {
          title: "Histórico de Qrcodes",
          desc:
            "Com o QR-Scan, você tem acesso ao histórico de todos os QR Codes que foram gerados e escaneados, para que não perca nenhum deles e possa acessá-los sempre que quiser. Se preferir, também é possível excluí-los.",
        },
      ],
    };
  },
};
</script>

<style></style>
