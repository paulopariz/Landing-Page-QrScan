<template>
  <div>
    <MyEclipse />

    <MyEclipse class="right-0 top-1/4" />

    <nav
      class="fixed top-0 w-screen py-9 bg-transparent border border-x-0 border-t-0 border-dark/50"
    >
      <div class="px-16 flex items-center justify-between bg-transparent">
        <img src="@/assets/img/logo.svg" alt="Logo" class="w-12 bg-transparent" />

        <div class="flex items-center gap-4">
          <button
            class="text-dark transition-all font-medium text-sm px-5 py-2 border-2 border-transparent bg-light hover:bg-transparent hover:text-white hover:border-light"
          >
            Acessar QR-Scan
          </button>

          <button
            class="text-dark transition-all font-medium text-sm px-5 py-2 border-2 border-transparent bg-light hover:bg-transparent hover:text-white hover:border-light"
          >
            Repositório
          </button>
        </div>
      </div>
    </nav>

    <header class="flex items-center">
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
