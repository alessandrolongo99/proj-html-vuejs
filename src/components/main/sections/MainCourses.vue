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
  height: 1000px;
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
    margin-top: 1rem
  }
  p{
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
    height: 50%;
    margin: 3.8rem 0;
    margin-left: 4rem;
  }
}
</style>