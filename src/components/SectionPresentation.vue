<template>
  <section class="w-11/12 m-auto mt-36">
    <div
      class="flex justify-between items-center max-lg:flex-col max-lg:items-start max-lg:gap-5"
    >
      <h1
        class="text-5xl font-bold w-1/3 text-black leading-tight max-lg:w-10/12 max-lg:text-4xl max-sm:text-3xl max-sm:w-full maxx"
      >
        Conheça mais sobre o QR-Scan
      </h1>

      <p
        class="text-black w-2/5 tracking-wide leading-7 max-lg:w-10/12 max-sm:text-sm max-sm:w-full"
      >
        O site oferece diversas funcionalidades feitas para você. Você pode gerar seus
        próprios QR codes e baixá-los para usá-los onde e como quiser. Além disso,
        lembre-se de que você também pode escanear outros QR codes para acessá-los. Que
        tal gerar um QR code agora e escaneá-lo em seguida?
      </p>
    </div>

    <div class="h-screen flex items-center gap-5 mt-16 max-lg:flex-col max-lg:h-full">
      <div
        class="w-2/5 h-full bg-light flex items-center justify-between flex-col gap-5 px-10 py-20 overflow-hidden max-lg:h-1/2 max-lg:w-full max-sm:py-6 max-sm:px-5"
      >
        <div class="flex flex-col gap-2 w-11/12 items-start max-sm:w-full">
          <h1 class="text-3xl font-medium text-black max-sm:text-2xl">Gerar QR-Code</h1>
          <p
            class="text-sm font-normal text-black leading-6 max-sm:text-xs max-sm:leading-5"
          >
            Com o QR-Scan, você pode gerar códigos QR para diversas redes sociais e sites,
            simplesmente inserindo um nome de usuário ou URL correto. Seu código QR estará
            pronto em questão de segundos.
          </p>
        </div>
        <img
          src="@/assets/img/PhoneGenerate.png"
          alt="Phone Generate"
          class="w-72 max-lg:w-56 max-sm:w-48"
        />
      </div>

      <div class="flex flex-col gap-5 w-3/5 h-full max-lg:w-full">
        <div
          class="w-full h-1/2 bg-black flex flex-col justify-between gap-4 px-20 py-10 overflow-hiddenmax-sm:py-6 max-sm:px-5"
        >
          <div class="flex flex-col gap-2 items-start lg:absolute">
            <h1 class="text-3xl font-medium text-white max-sm:text-2xl">
              QR-Code gerado
            </h1>
            <p
              class="text-sm font-normal text-white-2 w-4/5 leading-6 max-sm:text-xs max-sm:leading-6"
            >
              Após gerar o seu QR Code, você terá a opção de fazer o download do mesmo
              para utilizá-lo como quiser.
            </p>
          </div>
          <img
            src="@/assets/img/PhoneGenerated.png"
            alt="Phone Generated"
            class="w-[500px] m-auto max-sm:w-full"
          />
        </div>

        <div
          class="w-full h-1/2 bg-white-2 flex items-center justify-between px-20 py-5 overflow-hidden max-sm:flex-col max-sm:py-6 max-sm:px-5 max-sm:gap-5"
        >
          <div class="flex flex-col gap-2 items-start">
            <h1 class="text-3xl font-medium text-black max-sm:text-2xl">
              Escanear QR-Code
            </h1>
            <p
              class="text-sm font-normal text-black w-4/5 leading-6 max-xl:w-full max-sm:text-xs max-sm:leading-5"
            >
              Leia vários QR Codes aqui com sucesso! Lembre-se de limpar a câmera e
              centralizar o QR Code para que seja lido com precisão.
            </p>
          </div>
          <img src="@/assets/img/PhoneScan.png" alt="Phone Scan" class="w-52" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionPresentation",
};
</script>

<style></style>
