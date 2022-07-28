<template>
  <footer>
    <div class="container">
      <h1>Partners</h1>
      <p>
        Leverage agile frameworks to provide a robust synopsis for high level
        overviews. Iterative approaches to corporate strategy.
      </p>

      <div class="img-container">
        <div><img src="../../assets/img/partner-2.png" alt="" /></div>
        <div><img src="../../assets/img/partner-3.png" alt="" /></div>
        <div><img src="../../assets/img/partner-4.png" alt="" /></div>
        <div><img src="../../assets/img/partner-5.png" alt="" /></div>
        <div><img src="../../assets/img/partner-6.png" alt="" /></div>
        <div><img src="../../assets/img/partner-8.png" alt="" /></div>
        <div><img src="../../assets/img/partner-1.png" alt="" /></div>
        <div><img src="../../assets/img/partner-7.png" alt="" /></div>
      </div>
    </div>

    <div class="bg-wave">

    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
footer {
  margin-top: 3rem;
}

.bg-wave{
    background-image: url('../../assets/img/background-wave3.png');
    background-color: #fafafa;
    height: 300px;
    background-position: -60px 0;
    background-size: 2280px;
    background-repeat: no-repeat;
}

.img-container {
  width: 65%;
  margin: 0 auto;
}

h1 {
  font-family: "Fredoka One", cursive;
  color: #454545;
  font-size: 3.2rem;
  margin-top: 1rem;
  text-align: center;
}

p {
  font-family: "Roboto", sans-serif;
  color: #454545;
  font-size: 1.05rem;
  line-height: 1.8rem;
  text-align: center;
  width: 30%;
  margin: 2rem auto;
}

.img-container {
  display: flex;
  justify-content: space-between;
  img {
    height: 55px;
    filter: invert(55%) sepia(7%) saturate(35%) hue-rotate(21deg)
      brightness(99%) contrast(89%);
  }
}
</style>