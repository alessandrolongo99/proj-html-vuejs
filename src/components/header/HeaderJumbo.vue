<template>
  <div>
    <h1>Key to your success</h1>
    <p>
      EduPrime is the most versatile WordPress theme for educational purposes,
      showcasing universities, courses, secondary schools etc.
    </p>
    <div class="buttons">
      <button>
        <i class="fa-solid fa-magnifying-glass"></i> Search Courses
      </button>
      <button class="apply">
        <i class="fa-solid fa-user-plus"></i> Apply for university
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
h1 {
  font-family: "Fredoka One", cursive;
  color: #fff;
  text-align: center;
  font-size: 4rem;
  padding-top: 100px;
}

p {
  text-align: center;
  color: #fff;
  font-family: "Roboto", sans-serif;
  font-size: 1.5rem;
  width: 800px;
  margin: 0 auto;
  padding-top: 50px;
}

.buttons {
  padding-top: 50px;
  text-align: center;
}

button {
  margin: 0 1rem;
  border: none;
  border-radius: 40px;
  padding: 1.2rem 3rem;
  color: #fff;
  background-color: #e9d758;
  font-size: 1.2rem;
  font-family: "Fredoka One", cursive;
  &:hover {
    cursor: pointer;
    box-shadow: 0 5px 15px black;
    transition-property: box-shadow;
    transition-duration: .5s;
  }
  &.apply{
    background-color: #fff;
    color: #e56768;
  }
}
</style>