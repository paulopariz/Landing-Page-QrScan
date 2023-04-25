<template>
  <div class="h-screen">
    <MyHeader />

    <div>
      <MyTechs />
    </div>
  </div>
</template>

<script>
import MyTechs from "./components/MyTechs.vue";
import MyHeader from "./components/MyHeader.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    MyTechs,
  },
};
</script>

<style>
@import "~uikit/dist/css/uikit.min.css";

body {
  background-color: #fff;
}

h1,
h2,
h3,
p,
span,
a {
  font-family: "DM Sans", sans-serif;
}

*::-webkit-scrollbar {
  width: 7px;
}
*::-webkit-scrollbar-track {
  background: transparent;
}
*::-webkit-scrollbar-thumb {
  background-color: black;
  border-radius: 20px;
}
</style>
