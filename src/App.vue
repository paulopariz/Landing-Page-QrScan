<template>
  <div class="h-screen">
    <MyHeader />

    <div>
      <MyTechs />

      <SectionPresentation />

      <SectionHistory />

      <SectionEnter />
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
  </div>
</template>

<script>
import MyTechs from "./components/MyTechs.vue";
import MyHeader from "./components/MyHeader.vue";
import SectionPresentation from "./components/SectionPresentation.vue";
import SectionHistory from "./components/SectionHistory.vue";
import SectionEnter from "./components/SectionEnter.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    MyTechs,
    SectionPresentation,
    SectionHistory,
    SectionEnter,
  },
};
</script>

<style>
/* @import "~uikit/dist/css/uikit.min.css"; */

body {
  background-color: #fff;
  user-select: none;
  font-family: "DM Sans", sans-serif;
  color: #fff;
}

*::-webkit-scrollbar {
  width: 0px;
}
</style>
