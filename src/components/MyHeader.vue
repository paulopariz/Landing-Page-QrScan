<template>
  <div>
    <MyEclipse class="hidden" />

    <nav class="py-9 px-20 w-full flex items-center justify-center backdrop-blur-md">
      <div class="bg-black h-[0.1px] w-full"></div>
      <img src="@/assets/img/Group.svg" alt="Logo" class="w-[70px] px-5" />
      <div class="bg-black h-[0.1px] w-full"></div>
    </nav>

    <header
      class="flex items-center justify-between w-11/12 absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2"
    >
      <div class="flex flex-col gap-7 w-2/3">
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
          <button class="bg-light py-4 px-5 text-black transition-all btn2">
            <span class="transition-all font-medium">Acessar QR-Scan</span>
          </button>

          <button class="bg-black py-4 px-5 text-light transition-all btn1">
            <span class="transition-all font-medium">Acessar Repositório</span>
          </button>
        </div>
      </div>

      <MyPhone />
    </header>
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
  </div>
  <br />
</template>

<script>
import MyEclipse from "./MyEclipse.vue";
import MyPhone from "./MyPhone.vue";
export default {
  components: { MyEclipse, MyPhone },
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
</style>
