<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <Home/>
  </div>
</template>

<script>
import HelloWorld from "./components/home/Home";

export default {
  name: "App",
  components: {
    Home
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
