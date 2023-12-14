<template>
  <div id="app">
    <Misaka />
  </div>
</template>

<script>
import Misaka from './components/Misaka.vue'

export default {
  name: 'App',
  components: {
    Misaka
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
