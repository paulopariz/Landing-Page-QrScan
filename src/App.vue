<template>
  <main class="transition-all" id="appContent">
    <MyHeader />

    <MyTechs />

    <SectionPresentation />

    <SectionHistory />

    <SectionEnter />

    <MyFoorter />
  </main>
</template>

<script>
import AOS from "aos";

import MyTechs from "./components/MyTechs.vue";
import MyHeader from "./components/MyHeader.vue";
import SectionPresentation from "./components/SectionPresentation.vue";
import SectionHistory from "./components/SectionHistory.vue";
import SectionEnter from "./components/SectionEnter.vue";
import MyFoorter from "./components/MyFoorter.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    MyTechs,
    SectionPresentation,
    SectionHistory,
    SectionEnter,
    MyFoorter,
  },

  mounted() {
    AOS.init({
      once: true,
    });
  },
};
</script>

<style scoped>
body {
  background-color: #fff;
  user-select: none;
  font-family: "Saira", sans-serif;
  color: #fff;
}

#appContent {
  animation: app 1.2s both;
}

@keyframes app {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
