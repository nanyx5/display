<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <display></display>
  </div>
</template>

<script>
import Display from './views/display.vue'
export default {
  name: 'App',
  components: {
    Display
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
