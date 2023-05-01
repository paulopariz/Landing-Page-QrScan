<template>
  <div class="w-full h-screen p-20 bg-black mt-96 m-auto">
    <MyEclipse class="right-1" />
    <div
      class="mt-16 flex items-start justify-between w-3/4 absolute left-1/2 -translate-x-1/2"
    >
      <img src="@/assets/img/Untitled.png" class="w-96" alt="Phone History" />

      <div class="flex justify-end w-1/2">
        <h1 class="text-5xl font-bold text-white leading-snug">
          Gerencie seu histórico "Scan" e "Gerados"
        </h1>
      </div>
    </div>
  </div>
</template>

<script>
import MyEclipse from "./MyEclipse.vue";

export default {
  name: "SectionHistory",
  components: { MyEclipse },
};
</script>

<style></style>
