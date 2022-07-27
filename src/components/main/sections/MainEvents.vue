<template>
  <main>
    <img class="top-wave" src="../../../assets/svg/svg-0.svg" alt="">
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
main{
    background-color: #e56768;
    height: 1000px;
    position: relative;
    overflow-x: clip;
}

.top-wave{
    position: absolute;
    top: 0;
    transform: translate(0, -99%);
    display: block;
}
</style>