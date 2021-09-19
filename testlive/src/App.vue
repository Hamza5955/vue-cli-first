<template>
  <div id="app">
    <HelloWorld />
    <MonaLisa />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Monalisa from "./components/monalisa.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Monalisa,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
