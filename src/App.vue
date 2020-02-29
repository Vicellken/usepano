<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <usePano />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import usePano from "./components/pano"

export default {
  name: 'App',
  components: {
    // HelloWorld
    usePano
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
