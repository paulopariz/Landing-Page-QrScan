<template>
  <div class="h-screen">
    <MyHeader />

    <div>
      <CarouselQrScan />
    </div>
  </div>
</template>

<script>
import CarouselQrScan from "./components/CarouselQrScan.vue";
import MyHeader from "./components/MyHeader.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    CarouselQrScan,
  },
};
</script>

<style>
@import "~uikit/dist/css/uikit.min.css";

body {
  background-color: #fff;
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
