<template>
  <main>
    <h1>Latest Courses</h1>

    <div class="latest">
      <div class="card">
        <div>
          <img src="../../../assets/img/Decisions-icon.png" alt="" />
        </div>

        <h3>Make Better Decisions</h3>
        <span
          ><i class="fa-regular fa-user"></i> Teacher:
          <span class="bold">James Colins</span></span
        >
        <span
          ><i class="fa-solid fa-money-bill"></i> Price:
          <span class="bold">$21.00</span></span
        >

        <button><i class="fa-regular fa-eye"></i> View Course</button>
      </div>

      <div class="card">
        <div>
          <img src="../../../assets/img/Speaker-icon.png" alt="" />
        </div>

        <h3>How to be a speaker</h3>
        <span
          ><i class="fa-regular fa-user"></i> Teacher:
          <span class="bold">James Colins</span></span
        >
        <span
          ><i class="fa-solid fa-money-bill"></i> Price:
          <span class="bold">Free</span></span
        >
        <button><i class="fa-regular fa-eye"></i> View Course</button>
      </div>

      <div class="card">
        <div>
          <img src="../../../assets/img/Network-icon.png" alt="" />
        </div>

        <h3>Network Introduction</h3>
        <span
          ><i class="fa-regular fa-user"></i> Teacher:
          <span class="bold">James Colins</span></span
        >
        <span
          ><i class="fa-solid fa-money-bill"></i> Price:
          <span class="bold">Free</span></span
        >
        <button><i class="fa-regular fa-eye"></i> View Course</button>
      </div>

      <div class="card">
        <div>
          <img src="../../../assets/img/Brand-icon.png" alt="" />
        </div>

        <h3>Brand Management</h3>
        <span
          ><i class="fa-regular fa-user"></i> Teacher:
          <span class="bold">James Colins</span></span
        >
        <span
          ><i class="fa-solid fa-money-bill"></i> Price:
          <span class="bold">Free</span></span
        >
        <button><i class="fa-regular fa-eye"></i> View Course</button>
      </div>
    </div>

    <div class="flex-container">
      <div class="text-container">
        <img class="height-70" src="../../../assets/img/Exam-icon.png" alt="" />
        <h1>The most efficient examination method</h1>
        <p>
          EduPrime has gathered teachers from around the globe to brainstorm in
          order to facilitate the evaluation of our students. Every teacher from
          our university has an influence on how students are evaluated at
          his/her subject.
        </p>
        <button>Discover the Method</button>
      </div>

      <div class="img-container">
        <img src="../../../assets/img/Exam-Illustration.png" alt="" />
      </div>
    </div>

    <div class="flex-container bot-row">
      <div class="img-container">
        <img src="../../../assets/img/Girl-Illustration.png" alt="" />
      </div>

      <div class="text-container">
        <img class="height-70" src="../../../assets/img/Exam-icon-1.png" alt="" />
        <h1>Variable fees for international students</h1>
        <p>
          EduPrime has gathered teachers from around the globe to brainstorm in
          order to facilitate the evaluation of our students. Every teacher from
          our university has an influence on how students are evaluated at
          his/her subject.
        </p>
        <button>List of Fees</button>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
main {
  width: 65%;
  margin: 0 auto;
  margin-top: 10rem;
}

h1 {
  font-family: "Fredoka One", cursive;
  color: #454545;
  font-size: 3.2rem;
  margin-top: 1rem;
  margin-bottom: 2rem;
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

.flex-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 9rem;
}

.bot-row{
    margin-bottom: 4rem;
}

.height-70 {
  height: 70px;
}

.text-container {
  width: 50%;
}

.img-container {
  width: 40%;
  img {
    width: 100%;
  }
}

.latest {
  display: flex;
  justify-content: space-between;
  width: 100%;
  margin-bottom: 6rem;
  .card {
    padding: 0 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    position: relative;
    img {
      height: 70px;
      display: block;
      margin-bottom: 1rem;
    }
    h3 {
      font-family: "Fredoka One", cursive;
      text-align: center;
      color: #454545;
      margin-bottom: 0.6rem;
    }
    span {
      font-family: "Roboto", sans-serif;
      color: #8b8b8a;
      font-size: 1.05rem;
      line-height: 1.8rem;
      margin-bottom: 0.6rem;
    }
    .bold {
      color: #454545;
    }

    button {
      position: absolute;
      bottom: 0;
      left: 50%;
      width: 65%;
      transform: translate(-50%, 50%);
      font-family: "Fredoka One", cursive;
      border: none;
      border-radius: 40px;
      padding: 1rem 2rem;
      color: #fff;
      background-color: #e56768;
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
      font-size: 0.8rem;
      &:hover {
        cursor: pointer;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        transition-property: box-shadow;
        transition-duration: 0.5s;
      }
    }
  }
}
</style>