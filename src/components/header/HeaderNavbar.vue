<template>
  <nav>
    <div class="logo">
      <img src="../../assets/img/theme_eduprime_logo.png" alt="" />
    </div>
    <div class="right-nav">
      <ul>
        <li v-for="(item, index) in liItems" :key="index">
          {{ item.item }}
          <i v-if="item.dropDown" class="fa-solid fa-caret-down"></i>
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
        { item: "Home", dropDown: true },
        { item: "Courses", dropDown: true },
        { item: "About Us", dropDown: false },
        { item: "News", dropDown: true },
        { item: "Pages", dropDown: true },
        { item: "Contact", dropDown: false },
        { item: "Purchase", dropDown: false },
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
  &:hover {
    cursor: pointer;
    box-shadow: 0 5px 15px #000;
    transition-property: box-shadow;
    transition-duration: 0.5s;
  }
}
</style>