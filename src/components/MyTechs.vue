<template>
  <div>
    <div class="absolute right-0 z-10 -bottom-1/3 w-2/3 px-28 py-14 bg-black">
      <div class="flex items-center justify-between">
        <div v-for="tech in techs" :key="tech.id" class="flex items-center gap-3 w-64">
          <img :src="tech.icon" :alt="tech.name" class="w-16" />
          <div class="flex flex-col gap-1">
            <h1 class="tracking-wide text-lg text-light font-semibold">
              {{ tech.name }}
            </h1>
            <p class="text-white-2 font-medium text-xs">{{ tech.desc }}</p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="absolute right-0 -bottom-[35%] z-0 w-[67.6%] px-8 py-20 bg-transparent border-2 border-light border-r-0"
    ></div>
  </div>
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
