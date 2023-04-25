<template>
  <div class="w-11/12 m-auto h-screen flex items-center gap-5">
    <div
      class="w-2/5 h-full bg-light flex items-center justify-between flex-col px-10 py-20"
    >
      <div class="flex flex-col gap-2 w-11/12 items-start">
        <h1 class="text-3xl font-medium text-black">Gerar QR-Code</h1>
        <p class="text-sm font-normal text-black">
          Com o QR-Scan, você pode gerar códigos QR para diversas redes sociais e sites,
          simplesmente inserindo um nome de usuário ou URL correto. Seu código QR estará
          pronto em questão de segundos.
        </p>
      </div>
      <img src="@/assets/img/PhoneGenerate.png" alt="Phone Generate" class="w-72" />
    </div>

    <div class="flex flex-col gap-5 w-3/5 h-full">
      <div class="w-full h-1/2 bg-black flex flex-col justify-between gap-4 px-20 py-10">
        <div class="flex flex-col gap-2 items-start absolute">
          <h1 class="text-3xl font-medium text-white">QR-Code gerado</h1>
          <p class="text-sm font-normal text-white-2 w-4/5">
            Após gerar o seu QR Code, você terá a opção de fazer o download do mesmo para
            utilizá-lo como quiser.
          </p>
        </div>

        <img
          src="@/assets/img/PhoneGenerated.png"
          alt="Phone Generated"
          class="w-[550px] m-auto"
        />
      </div>

      <div class="w-full h-1/2 bg-white-2 flex items-center justify-between px-20 py-5">
        <div class="flex flex-col gap-2 items-start">
          <h1 class="text-3xl font-medium text-black">Escanear QR-Code</h1>
          <p class="text-sm font-normal text-black w-4/5">
            Leia vários QR Codes aqui com sucesso! Lembre-se de limpar a câmera e
            centralizar o QR Code para que seja lido com precisão.
          </p>
        </div>
        <img src="@/assets/img/PhoneScan.png" alt="Phone Scan" class="w-52" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionPresentation",
};
</script>

<style></style>
