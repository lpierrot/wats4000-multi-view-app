<template>
  <div id="app">
    <h1>Home</h1>
    <hr>
    <router-link to="/">Home</router-link>
    <hr>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  width: 75%;
  min-height: 100vh;
  height: 100%;
  margin: 0 auto;
  background: #fff;
  padding: 2rem;
}
nav {
  color: blue;
}

body,
html {
  background: #666;
  margin: 0;
  padding: 0;
}
</style>
