<template>
  <footer>
    <div class="container">
      <div class="flex-container">
        <div class="edu-prime">
          <img src="../../assets/img/theme_eduprime_logo.png" alt="" />
          <p>
            EduPrime is the most versatile WordPress theme for educational
            purposes, showcasing universities, courses, secondary schools etc.
          </p>
          <button><i class="fa-brands fa-2x fa-facebook-f"></i></button>
          <button><i class="fa-brands fa-2x fa-twitter"></i></button>
          <button><i class="fa-brands fa-2x fa-instagram"></i></button>
        </div>

        <div class="get-edu">
          <h3>Get EduPrime</h3>
          <ul>
            <li v-for="(link, index) in getEdu" :key="index">{{ link }}</li>
          </ul>
        </div>

        <div class="networking">
          <h3>Networking</h3>
          <ul>
            <li v-for="(link, index) in networking" :key="index">{{ link }}</li>
          </ul>
        </div>

        <div class="search">
          <div class="search-bar">
            <input type="text" placeholder="Search..." />
            <button><i class="fa-solid fa-magnifying-glass"></i></button>
          </div>

          <h3>Search categories</h3>

          <div class="tags-container">
            <span v-for="(tag, index) in tags" :key="index">{{ tag }}</span>
          </div>

          <span class="copy">ModelTheme. All rights reserved.</span>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data: function () {
    return {
      getEdu: [
        "Request a website",
        "Browse Themes",
        "Payment options",
        "Support System",
        "Checkout",
        "Purchase Theme",
      ],
      networking: [
        "Purchase Theme",
        "Our Benefits",
        "Our Team",
        "Our Service",
        "Other Products",
        "My account",
      ],
      tags: [
        "ECONOMY",
        "DESIGN",
        "COACHING",
        "BUSINESS",
        "MEDICINE",
        "LAW",
        "FITNESS",
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
footer {
  background-color: #e56768;
  padding-top: 10rem;
}

.container {
  padding-bottom: 5rem;
}

.flex-container {
  display: flex;
  justify-content: space-between;
  width: calc(65% + 2rem);
  margin: 0 auto;
}

.edu-prime,
.search {
  width: calc(100% / 3);
  margin: 0 1rem;
  img {
    height: 70px;
    margin-bottom: 2rem;
  }
}

.search {
  text-align: right;
}

.copy {
  border: none;
  padding: 0;
  color: #e9d758;
  font-size: 1rem;
}

p,
span {
  font-family: "Roboto", sans-serif;
  color: #fff;
  font-size: 1.05rem;
  line-height: 1.8rem;
  margin-bottom: 2rem;
}

.tags-container {
  display: flex;
  width: 100%;
  flex-wrap: wrap;
  flex-direction: row-reverse;
  margin-bottom: 1rem;
  span {
    margin-bottom: 1rem;
    &:hover {
      cursor: pointer;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
      transition-property: box-shadow;
      transition-duration: 0.5s;
    }
  }
}

span {
  border: 1px solid #fff;
  border-radius: 40px;
  padding: 0.2rem 1rem;
  margin-left: 0.5rem;
  font-size: 0.6rem;
}

button {
  border: 2px solid #e9d758;
  background-color: transparent;
  color: #fff;
  border-radius: 50%;
  height: 4rem;
  width: 4rem;
  margin-right: 1rem;
  &:hover {
    cursor: pointer;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    transition-property: box-shadow;
    transition-duration: 0.5s;
  }
}

.get-edu,
.networking {
  width: calc((100% / 3) / 2);
  margin: 0 1rem;
}

h3 {
  font-family: "Fredoka One", cursive;
  color: #fff;
  margin-bottom: 2rem;
}

li {
  list-style: none;
  font-family: "Roboto", sans-serif;
  color: #fff;
  font-size: 1.05rem;
  line-height: 2.4rem;
  &:hover {
    text-decoration: underline;
    cursor: pointer;
  }
}

.search-bar {
  position: relative;
  margin-bottom: 2rem;
  input {
    width: 100%;
  }
  button {
    position: absolute;
    top: 0;
    right: -1rem;
    border: none;
    background-color: #e9d758;
    color: #fff;
    height: 4rem;
    border-radius: 50%;
    width: 4rem;
    &:hover {
      cursor: pointer;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
      transition-property: box-shadow;
      transition-duration: 0.5s;
    }
  }
}

input {
  font-family: "Roboto", sans-serif;
  border: none;
  border-radius: 40px;
  padding: 0.3rem 2rem;
  height: 4rem;
}
</style>