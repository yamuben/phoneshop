<template>
  <div class="container">
    <img src="../assets/logo.png" alt="logo" height="100%" />
    <div class="menuContainer">
      <a href="#">Home</a>
      <a href="#">About Us</a>
      <a href="#">Contact Us</a>
    </div>
    <div class="menuContainer sign">
      <a href="#">Log in</a>
      <button>Signup</button>
    </div>
  </div>
</template>
<script>
export default {
  name: "HeaderComponent",
};
</script>
<style>
.sign{
    gap:1rem
}
.container {
  width: 100%;
  height: 6rem;
  padding: 1rem 2rem;
  display: flex;

  justify-content: space-between;
  align-items: center;
  background: rgb(205, 219, 219);
  text-align: center;
}
.container button {
  padding: 1rem;
  width: 7rem;
  border-radius: 20px;
  font-size: 1rem;
}
.menuContainer a:hover {
  /* background: rgb(158, 196, 174);
   */

   font-weight: 600;
}
.menuContainer a {
  padding: 0.5rem;
  /* background: whitesmoke; */
  text-decoration: none;
  width: 130px;
  font-weight: lighter;
  color: black;
}
.menuContainer {
  /* width: 40%; */
  display: flex;
  justify-content: center;
  align-items: center;
  /* gap:1rem; */
  text-align: center;
  /* background: yellow; */
}
</style>
