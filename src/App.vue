<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%" />
    <RunningBalance msg="Vue in CodeSandbox!" />
  </div>
</template>

<script>
import RunningBalance from "./components/RunningBalance";
export default {
  name: "App",
  components: {
    RunningBalance,
  },
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
