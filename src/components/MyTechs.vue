<template>
  <section>
    <div class="w-full px-36 py-14 mt-36 bg-black max-xl:px-20 max-lg:px-6">
      <div class="flex items-center justify-between max-md:flex-col max-md:gap-7">
        <div
          v-for="tech in techs"
          :key="tech.id"
          class="flex items-center gap-3 w-64"
          data-aos="fade-up"
        >
          <img :src="tech.icon" :alt="tech.name" class="w-16 max-lg:w-12 max-md:w-10" />
          <div class="flex flex-col gap-1">
            <h1 class="tracking-wide text-lg text-light font-semibold">
              {{ tech.name }}
            </h1>
            <p class="text-white-2 font-medium text-xs">{{ tech.desc }}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      techs: [
        {
          icon: require("@/assets/img/iconVue.svg"),
          name: "Vue.js",
          desc: "100% do site feito em vue",
        },
        {
          icon: require("@/assets/img/iconTailwind.svg"),
          name: "TailwindCSS",
          desc: "Interface desenvolvida com o auxílio do Tailwind",
        },
        {
          icon: require("@/assets/img/iconFigma.svg"),
          name: "Figma",
          desc: "Interface do sistema integrado ao Figma",
        },
      ],
    };
  },
};
</script>

<style></style>
