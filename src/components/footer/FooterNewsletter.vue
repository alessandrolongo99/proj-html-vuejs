<template>
  <footer>
    <h1>Subscribe Now to Our Newsletter !</h1>
    <div>
      <input type="text" placeholder="Email address..." />
      <button><i class="fa-solid fa-2x fa-paper-plane"></i></button>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
footer {
  width: 65%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 12rem;
}

h1 {
  font-family: "Fredoka One", cursive;
  color: #fff;
  font-size: 2.5rem;
}

div {
  position: relative;
}

input {
  font-family: "Roboto", sans-serif;
  border: none;
  border-radius: 40px;
  padding: 0.3rem 2rem;
  height: 4rem;
  width: 400px;
}

button {
  position: absolute;
  top: 0;
  right: 0;
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
</style>