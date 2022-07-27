<template>
  <main>
    <div class="courses-container">
      <div class="text-container">
        <img src="../../../assets/img/Books-icon.png" alt="" />
        <h1>Thousands of courses for any type of student</h1>
        <p>
          At EduPrime, it doesn't matter what domain you wish to pursue a career
          in. Here you can find a course that satisfies your needs within a
          click away and applies for a course in a matter of minutes. EduPrime
          is ranked as the most versatile university in the world, thanks to the
          number of courses it provides.
        </p>
        <button>Browse through courses</button>
      </div>
      <div class="img-container">
        <img src="../../../assets/img/Graduation-Illustration.png" alt="" />
      </div>
    </div>

    <div class="faculties">
      <h1>Faculties available at EduPrime</h1>
      <p>
        A single university with a load of courses, tailored to satisfy any
        student's needs.
      </p>

      <div class="faculties-bar">
        <div class="faculties-container">
          <div>
            <img src="../../../assets/img/Gavel-v2.png" alt="" />
            <span>Law Faculty</span>
          </div>
          <div>
            <img src="../../../assets/img/Coins-tabs-v2.png" alt="" />
            <span>Economy</span>
          </div>
          <div>
            <img src="../../../assets/img/Medicine-tabs-v2.png" alt="" />
            <span>Medicine</span>
          </div>
          <div>
            <img src="../../../assets/img/Computer-tabs-v2.png" alt="" />
            <span>Computer Science</span>
          </div>
          <div>
            <img src="../../../assets/img/Palette-tabs-v2.png" alt="" />
            <span>Graphic Design</span>
          </div>
        </div>
      </div>
    </div>

    <div class="law-faculty">
      <div>
        <img
          src="../../../assets/img/Gavel-Illustration-e1556884768193.png"
          alt=""
        />
      </div>
      <div class="law-faculty-text">
        <h1>Law Faculty</h1>
        <p>
          Learning from world-leading academics and practitioners, you'll not
          only receive an out standing grounding in the theory of law, but you
          will be able to understand how those principles are applied in
          practice through a range of student-led activities and competitions.
        </p>
        <button>Read More</button>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
main {
  background-image: url("../../../assets/img/home-background.png");
  background-repeat: no-repeat;
  margin-top: 1rem;
  margin-bottom: 15rem;
}

.courses-container {
  width: 65%;
  margin: 0 auto;
  display: flex;
  padding-top: 6rem;
}

.text-container {
  width: 50%;
  img {
    height: 70px;
  }
  h1 {
    font-family: "Fredoka One", cursive;
    color: #454545;
    font-size: 3.2rem;
    margin-top: 1rem;
  }
  p {
    font-family: "Roboto", sans-serif;
    color: #8b8b8a;
    margin-top: 2rem;
    font-size: 1.05rem;
    line-height: 1.8rem;
  }
  button {
    font-family: "Fredoka One", cursive;
    margin-top: 2rem;
    border: none;
    border-radius: 40px;
    padding: 1.2rem 3rem;
    color: #fff;
    background-color: #e9d758;
    font-size: 1.2rem;
    &:hover {
      cursor: pointer;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
      transition-property: box-shadow;
      transition-duration: 0.5s;
    }
  }
}

.img-container {
  width: 50%;
  img {
    display: block;
    height: 400px;
    margin: 3.8rem 0;
    margin-left: 4rem;
  }
}

.faculties {
  margin-top: 5rem;

  h1 {
    font-family: "Fredoka One", cursive;
    color: #454545;
    font-size: 3.2rem;
    margin-top: 1rem;
    text-align: center;
  }

  p {
    font-family: "Roboto", sans-serif;
    color: #8b8b8a;
    font-size: 1.05rem;
    line-height: 1.8rem;
    text-align: center;
    width: 370px;
    margin: 2rem auto;
  }
}
.faculties-bar {
  width: 100%;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}

.faculties-container {
  display: flex;
  justify-content: center;
  width: 65%;
  margin: 0 auto;
  div {
    height: 100%;
    padding: 2rem 3rem;
    border: 1px solid rgba(0, 0, 0, 0.1);
    text-align: center;
    width: calc(100% / 5);
    img {
      height: 70px;
      display: block;
      margin: 0 auto;
      margin-bottom: 1rem;
    }
    span {
      font-family: "Fredoka One", cursive;
      color: #e56768;
    }
  }
}

.law-faculty {
  display: flex;
width: 65%;
margin: 0 auto;
margin-top: 5rem;
  div {
    width: 50%;
    img{
        display: block;
        margin: 0 auto;
    }
  }
}

.law-faculty-text {
  h1 {
    font-family: "Fredoka One", cursive;
    color: #454545;
    font-size: 2.5rem;
    margin-top: 1rem;
  }
  p {
    font-family: "Roboto", sans-serif;
    color: #8b8b8a;
    margin-top: 2rem;
    font-size: 1.05rem;
    line-height: 1.8rem;
  }
  button {
    font-family: "Fredoka One", cursive;
    margin-top: 2rem;
    border: none;
    border-radius: 40px;
    padding: 1.2rem 3rem;
    color: #fff;
    background-color: #e56768;
    font-size: 1.2rem;
    &:hover {
      cursor: pointer;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
      transition-property: box-shadow;
      transition-duration: 0.5s;
    }
  }
}
</style>