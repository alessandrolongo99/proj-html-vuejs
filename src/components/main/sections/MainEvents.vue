<template>
  <main>
    <img class="top-wave" src="../../../assets/svg/svg-0.svg" alt="" />
    <img class="clock" src="../../../assets/img/Clock-and-Bell.png" alt="" />
    <h1><mark>University Year</mark></h1>

    <div class="time-line">
      <img src="../../../assets/img/Timeline-Item.png" alt="" />
      <div class="demo">
        <h3>Demo Classes</h3>
        <p>
          In the first week, students try to accommodate with the teaching style
          and choose their optional courses.
        </p>
      </div>

      <div class="graduation">
        <h3>Graduation Day</h3>
        <p>
          On the day of graduation, all students gather for the ceremony and
          then network and party among others.
        </p>
      </div>

      <div class="orientation">
        <h3>Orientation</h3>
        <p>
          First day of the university year, all students gather for the opening
          ceremony and then network with others.
        </p>
      </div>

      <div class="evaluation">
        <h3>Evaluation</h3>
        <p>
          At the end of a semester, students take a general evaluation test for
          every subject they're learning.
        </p>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
main {
  background-color: #e56768;
  height: 1000px;
  position: relative;
  overflow-x: clip;
  padding-top: 5rem;
}

.top-wave {
  position: absolute;
  top: 0;
  transform: translate(0, -99%);
  display: block;
}

.clock {
  height: 70px;
  display: block;
  margin: 0 auto;
}

h1 {
  font-family: "Fredoka One", cursive;
  text-align: center;
  font-size: 4rem;
  margin-top: 1.6rem;
}

mark {
  background-color: rgb(221, 0, 0);
  color: #fff;
}

.time-line {
  width: 65%;
  margin: 0 auto;
  position: relative;
  img {
    display: block;
    width: 100%;
    margin: 13rem 0;
  }
  h3 {
    font-family: "Fredoka One", cursive;
    color: #fff;
    margin-bottom: 1rem;
  }

  p {
    font-family: "Roboto", sans-serif;
    color: #fff;
    width: 400px;
    line-height: 1.8rem;
  }
  .demo {
    text-align: center;
    position: absolute;
    top: -120px;
    left: 295px;
  }

  .graduation {
    text-align: center;
    position: absolute;
    top: -120px;
    left: 800px;
  }

  .orientation {
    text-align: center;
    position: absolute;
    bottom: -120px;
    left: 35px;
  }

  .evaluation {
    text-align: center;
    position: absolute;
    bottom: -120px;
    left: 545px;
  }
}
</style>