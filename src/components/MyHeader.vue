<template>
  <div>
    <nav
      class="py-9 px-20 w-full flex items-center justify-center backdrop-blur-md max-lg:py-5 max-sm:px-6"
    >
      <div class="bg-black h-[0.1px] w-full"></div>
      <img src="@/assets/img/Group.svg" alt="Logo" class="w-[70px] px-5" />
      <div class="bg-black h-[0.1px] w-full"></div>
    </nav>

    <header
      class="flex items-center justify-between m-auto w-full lg:absolute lg:top-1/2 lg:left-1/2 lg:-translate-x-1/2 lg:-translate-y-1/2 lg:w-11/12 max-lg:flex-col max-lg:w-full max-lg:gap-11 max-lg:mt-5 max-sm:gap-6"
    >
      <div
        class="flex flex-col gap-7 w-3/5 max-xl:w-2/3 max-lg:gap-4 max-md:w-11/12 max-sm:w-full max-sm:px-6 max-sm:gap-2"
      >
        <h1
          class="text-black font-medium text-6xl max-xl:text-5xl max-lg:text-4xl max-sm:text-3xl"
        >
          Gere e escaneie QR Codes de forma fácil
        </h1>

        <p class="text-black/90 tracking-wide max-xl:text-sm max-sm:text-xs">
          Com o QR-Scan, você pode criar e escanear QR Codes de forma rápida e fácil.
          Use-o para gerar QR Codes para suas redes sociais favoritas, como Instagram,
          Twitter, LinkedIn, ou mesmo para seu site pessoal. Experimente agora e veja como
          é simples!
        </p>

        <div
          class="flex w-full items-center justify-between gap-3 mt-3 max-sm:flex-col max-sm:gap-2"
        >
          <button
            class="bg-light py-4 px-5 text-black transition-all max-lg:py-3 max-sm:py-2 btn2"
          >
            <span class="transition-all font-medium max-xl:text-sm max-sm:text-xs"
              >Acessar QR-Scan</span
            >
          </button>

          <button
            class="bg-black py-4 px-5 text-light transition-all max-lg:py-3 max-sm:py-2 btn1"
          >
            <span class="transition-all font-medium max-xl:text-sm max-sm:text-xs"
              >Acessar Repositório</span
            >
          </button>
        </div>
      </div>

      <MyPhone />
    </header>
  </div>
  <br />
</template>

<script>
import MyPhone from "./MyPhone.vue";
export default {
  components: { MyPhone },
  name: "MyNav",
};
</script>

<style scoped>
button {
  border: none;
  display: inline-block;
  font-size: 15px;
  font-weight: 600;
  width: 100%;
  text-transform: uppercase;
  cursor: pointer;
  transform: skew(-21deg);
}

span {
  display: inline-block;
  transform: skew(21deg);
}

.btn1::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  right: 100%;
  left: 0;
  background: #fdb623;
  opacity: 1;
  z-index: -1;
  transition: all 0.5s;
}

.btn2::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  right: 100%;
  left: 0;
  background: #000;
  opacity: 1;
  z-index: -1;
  transition: all 0.5s;
}

button:hover {
  color: #000;
}

button:hover:nth-child(1) {
  color: #fdb623;
}

button:hover::before {
  left: 0;
  right: 0;
}

@media (max-width: 642px) {
  button {
    transform: skew(0deg);
  }
  span {
    transform: skew(0deg);
  }
}
</style>
