<template>
  <div id="app">
    <HeaderBar />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld />
  </div>
</template>

<script>
import HeaderBar from "./components/header-bar";
import HelloWorld from "./components/HelloWorld";
import store from "../store";

export default {
  name: "App",
  store,
  components: { HeaderBar, HelloWorld },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
