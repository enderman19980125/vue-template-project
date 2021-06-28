<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Brief/>
  </div>
</template>

<script>
import Brief from "./components/personal_introduction/Brief.vue";

export default {
  name: 'App',
  components: {
    Brief,
  }
}
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
