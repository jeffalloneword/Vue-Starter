<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <InputTest/>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld"
import InputTest from "./components/InputTest"

export default {
  name: "App",
  components: {
    InputTest,
    HelloWorld
  }
}
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
