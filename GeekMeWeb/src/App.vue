<template>
  <div id="app">
    <img alt="GeekMelogo" src="./assets/logo.png">
    <header msg="GeekMe start"/>
  </div>
</template>

<script>
import header from './components/header.vue'

export default {
  name: 'app',
  components: {
    header
  }
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
