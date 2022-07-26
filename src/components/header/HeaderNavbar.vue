<template>
  <nav>
    <div class="logo">
      <img src="../../assets/img/theme_eduprime_logo.png" alt="" />
    </div>
    <div class="right-nav">
      <ul>
        <li v-for="(item, index) in liItems" :key="index">
          {{ item }} <i class="fa-solid fa-caret-down"></i>
        </li>
      </ul>
      <button>VIEW COURSES</button>
    </div>
  </nav>
</template>

<script>
export default {
  data: function () {
    return {
      liItems: [
        `Home`,
        `Courses`,
        `About Us`,
        `News`,
        `Pages`,
        `Contact`,
        `Purchase`,
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
* {
  font-family: "Fredoka One", cursive;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 150px;
  padding: 0 3rem;
  color: #fff;
}

img {
  height: 50px;
}

.right-nav {
  display: flex;
  align-items: center;
}

ul {
  display: flex;
}

li {
  list-style: none;
  margin-left: 3rem;
  &:hover {
    color: #e9d758;
    cursor: pointer;
  }
}

button {
  margin-left: 3rem;
  border: none;
  border-radius: 40px;
  padding: 1.2rem 3rem;
  color: #fff;
  background-color: #e9d758;
  font-size: 1.2rem;
  &:hover{
    cursor: pointer;
    box-shadow: inset 0 0 10px;
  }
}
</style>