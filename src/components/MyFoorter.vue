<template>
  <footer aria-label="Site Footer" class="bg-black pt-36">
    <div class="relative mx-auto max-w-screen-xl px-4 py-16 sm:px-6 lg:px-8 lg:pt-24">
      <div class="absolute end-4 top-4 sm:end-6 sm:top-6 lg:end-8 lg:top-8">
        <button
          @click="backToTop"
          class="inline-block rounded-full bg-light p-2 text-black shadow transition sm:p-3 lg:p-4"
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
            class="mx-auto mt-6 max-w-md text-center leading-relaxed text-gray-500 lg:text-left"
          >
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt
            consequuntur amet culpa cum itaque neque.
          </p>
        </div>

        <nav aria-label="Footer Nav" class="mt-12 lg:mt-0">
          <ul
            class="flex flex-wrap justify-center gap-6 md:gap-8 lg:justify-end lg:gap-12"
          >
            <li>
              <a class="text-gray-700 transition hover:text-gray-700/75" href="/">
                About
              </a>
            </li>

            <li>
              <a class="text-gray-700 transition hover:text-gray-700/75" href="/">
                Services
              </a>
            </li>

            <li>
              <a class="text-gray-700 transition hover:text-gray-700/75" href="/">
                Projects
              </a>
            </li>

            <li>
              <a class="text-gray-700 transition hover:text-gray-700/75" href="/">
                Blog
              </a>
            </li>
          </ul>
        </nav>
      </div>

      <p class="mt-12 text-center text-sm text-gray-500 lg:text-right">
        Copyright &copy; 2022. All rights reserved.
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
