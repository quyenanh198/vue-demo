<template>
  <div id="app">
    <nav-menu></nav-menu>
    <img src="./assets/logo.png">
    <router-view></router-view>
    <p>ádfasdflka sjdf</p>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
