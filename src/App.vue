<template>
  <div id="app">
    <Grid msg="Welcome to the Social Media Feed App"/>
  </div>
</template>

<script>
import Grid from './components/Grid.vue'
import Nav from './components/Nav.vue'

export default {
  name: 'app',
  components: {
    Grid,
    Nav
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
