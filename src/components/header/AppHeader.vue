<template>
  <header>
    <HeaderNavbar />
    <HeaderJumbo />
    <img src="../../assets/img/Wave-1.png" alt="Wave-1" />
  </header>
</template>

<script>
import HeaderNavbar from "./HeaderNavbar.vue";
import HeaderJumbo from "./HeaderJumbo.vue";

export default {
  name: "AppHeader",
  components: {
    HeaderNavbar,
    HeaderJumbo,
  },
};
</script>

<style lang="scss" scoped>
header {
  background: linear-gradient(#da5f60e6, #da5f60e6),
    url("../../assets/img/theme_slider2_bg-1.jpg");
  background-repeat: no-repeat;
  height: 850px;
  position: relative;
}

img {
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>