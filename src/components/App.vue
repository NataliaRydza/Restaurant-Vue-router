<template>
  <div class="container">
    <div class="offer">
      <router-link to="/home" class="menuItem">Home</router-link>
      <router-link to="/menu" class="menuItem">Menu</router-link>
      <router-link to="/contact" class="menuItem">Contact</router-link>
    </div>
    <h1>Vue router</h1>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="css">
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
  background-color: #ffebcd;
}

.offer {
  background-color: burlywood;
  margin: 0;
  padding: 10px;
  text-align: center;
  border-radius: 10px;
}
h1 {
  padding-left: 30px;
}
.menuItem {
  padding: 15px;
  text-decoration: none;
  color: black;
}
.menuItem:hover {
  color: grey
}
</style>
