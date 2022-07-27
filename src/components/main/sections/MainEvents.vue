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

    <img
      class="clock"
      src="../../../assets/img/upcoming-events-calendar-icon.png"
      alt=""
    />
    <h1 class="upcoming">Upcoming Events</h1>

    <div class="coaching-sessions">
      <div class="card">
        <h2>Coaching Sessions</h2>
        <span><i class="fa-solid fa-calendar-days"></i> 20 May 21:30 PM</span>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit, sed do
          eiusmod tempor[...]
        </p>
        <button><i class="fa-solid fa-plus"></i> Find More</button>
      </div>

      <div class="card">
        <h2>Coaching Sessions</h2>
        <span><i class="fa-solid fa-calendar-days"></i> 24 Mar 18:00 PM</span>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit, sed do
          eiusmod tempor[...]
        </p>
        <button><i class="fa-solid fa-plus"></i> Find More</button>
      </div>

      <div class="card">
        <h2>Coaching Sessions</h2>
        <span><i class="fa-solid fa-calendar-days"></i> 12 Feb 13:30 PM</span>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit, sed do
          eiusmod tempor[...]
        </p>
        <button><i class="fa-solid fa-plus"></i> Find More</button>
      </div>
    </div>

    <button class="view-all">View All Events</button>

    <img class="bot-wave" src="../../../assets/svg/svg-1.svg" alt="" />
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
main {
  background-color: #e56768;
  position: relative;
  overflow-x: clip;
  padding-top: 5rem;
  padding-bottom: 3rem;
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
  color: #fff;
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

.upcoming {
  margin-bottom: 3rem;
}

.coaching-sessions {
  width: calc(65% + 2rem);
  margin: 0 auto;
  display: flex;
  text-align: center;
  h2 {
    font-family: "Fredoka One", cursive;
    text-align: center;
    color: #454545;
  }
  p,
  span {
    font-family: "Roboto", sans-serif;
    color: #8b8b8a;
    font-size: 1.05rem;
    line-height: 1.8rem;
  }
  span {
    font-size: 0.8rem;
    margin: 0.8rem 0;
  }
  .card {
    position: relative;
    background-color: #fff;
    width: calc(100% / 3);
    margin: 0 1rem;
    border-radius: 15px;
    padding: 3rem 2rem;
    button {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translate(-50%, 50%);
      font-family: "Fredoka One", cursive;
      margin-top: 2rem;
      border: none;
      border-radius: 40px;
      padding: 1rem 2rem;
      color: #fff;
      background-color: #e56768;
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
      font-size: 1.2rem;
      display: block;
      &:hover {
        cursor: pointer;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        transition-property: box-shadow;
        transition-duration: 0.5s;
      }
    }
  }
}

.view-all {
  font-family: "Fredoka One", cursive;
  margin-top: 2rem;
  border: none;
  border-radius: 40px;
  padding: 1.2rem 3rem;
  color: #fff;
  background-color: #e9d758;
  font-size: 1.2rem;
  margin: 5rem auto;
  display: block;
  &:hover {
    cursor: pointer;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    transition-property: box-shadow;
    transition-duration: 0.5s;
  }
}

.bot-wave {
  position: absolute;
  bottom: 0;
  transform: translate(-5%, 99%);
  display: block;
}
</style>