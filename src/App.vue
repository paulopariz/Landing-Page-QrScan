<template>
  <div class="bg-black h-screen">
    <MyHeader />
  </div>
</template>

<script>
import MyHeader from "./components/MyHeader.vue";

export default {
  name: "App",
  components: {
    MyHeader,
  },
};
</script>

<style>
@import "~uikit/dist/css/uikit.min.css";

* {
  background-color: #000;
  color: #d9d9d9;
}

h1,
h2,
h3,
p,
span,
a {
  font-family: "DM Sans", sans-serif;
}
</style>
