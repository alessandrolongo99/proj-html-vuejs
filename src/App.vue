<template>
  <div id="app">
    <AppHeader />
    <AppMain />
  </div>
</template>

<script>
import AppHeader from "./components/header/AppHeader.vue";
import AppMain from "./components/main/AppMain.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap");
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>