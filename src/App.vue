<template>
  <div class="h-screen">
    <MyHeader />

    <div class="hidden">
      <MyTechs />

      <SectionPresentation />

      <SectionHistory />
    </div>
  </div>
</template>

<script>
import MyTechs from "./components/MyTechs.vue";
import MyHeader from "./components/MyHeader.vue";
import SectionPresentation from "./components/SectionPresentation.vue";
import SectionHistory from "./components/SectionHistory.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    MyTechs,
    SectionPresentation,
    SectionHistory,
  },
};
</script>

<style>
/* @import "~uikit/dist/css/uikit.min.css"; */

body {
  background-color: #fff;
  user-select: none;
  font-family: "DM Sans", sans-serif;
}

*::-webkit-scrollbar {
  width: 0px;
}
</style>
