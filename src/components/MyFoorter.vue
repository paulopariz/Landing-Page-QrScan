<template>
  <footer aria-label="Site Footer" class="bg-black pt-36">
    <div
      class="relative mx-auto max-w-screen-xl px-4 py-16 sm:px-6 lg:px-8 lg:pt-24"
      data-aos="fade-up"
    >
      <div class="absolute end-4 top-4 sm:end-6 sm:top-6 lg:end-8 lg:top-8">
        <button
          @click="backToTop"
          class="inline-block rounded-full bg-light p-2 text-black shadow transition-all hover:scale-95 sm:p-3 lg:p-4"
        >
          <span class="sr-only">Back to top</span>

          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M14.707 12.707a1 1 0 01-1.414 0L10 9.414l-3.293 3.293a1 1 0 01-1.414-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 010 1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </button>
      </div>

      <div class="lg:flex lg:items-end lg:justify-between">
        <div>
          <div class="flex justify-center items-center gap-5 text-light lg:justify-start">
            <img src="@/assets/img/logo.svg" alt="Logo" class="w-11" />
            <h1 class="uppercase text-lg font-semibold text-white">QR-Scan</h1>
          </div>

          <p
            class="mx-auto mt-6 max-w-md text-center leading-relaxed text-white-2/60 lg:text-left"
          >
            Conheça todas as funcionalidades do QR-Scan e acompanhe-me nas redes sociais
            para ver mais do meu trabalho.
          </p>
        </div>

        <nav aria-label="Footer Nav" class="mt-12 lg:mt-0">
          <ul
            class="flex flex-wrap justify-center gap-6 md:gap-8 lg:justify-end lg:gap-12"
          >
            <li data-aos="fade-up" data-aos-duration="1100">
              <a
                class="text-white transition-all hover:text-light"
                target="_blank"
                href="https://github.com/paulopariz"
              >
                Github
              </a>
            </li>

            <li data-aos="fade-up" data-aos-duration="1500">
              <a
                class="text-white transition-all hover:text-light"
                target="_blank"
                href="https://paulopariz.vercel.app/"
              >
                Portfólio
              </a>
            </li>

            <li data-aos="fade-up" data-aos-duration="1800">
              <a
                class="text-white transition-all hover:text-light"
                target="_blank"
                href="https://www.linkedin.com/in/paulopariz/"
              >
                LinkedIn
              </a>
            </li>

            <li data-aos="fade-up" data-aos-duration="2000">
              <a
                class="text-white transition-all hover:text-light"
                target="_blank"
                href="https://www.instagram.com/parizpaulo_/"
              >
                Instagram
              </a>
            </li>
          </ul>
        </nav>
      </div>

      <p class="mt-12 text-center text-sm text-white-2/60 lg:text-right">
        <a href="https://paulopariz.vercel.app" target="_blank">Paulo Pariz</a> &copy;
        2023. Todos os direitos reservados
      </p>
    </div>
  </footer>
</template>

<script>
export default {
  methods: {
    backToTop() {
      window.scroll({ top: 0, left: 0, behavior: "smooth" });
    },
  },
};
</script>

<style></style>
