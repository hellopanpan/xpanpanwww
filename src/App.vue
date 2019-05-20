<template>
  <div id="app">
    <Index></Index>
  </div>
</template>

<script>
import Index from './views/index.vue'

export default {
  name: 'app',
  components: {
    Index
  }
}
</script>

<style>
#app {
  width: 100%;
  height: 100%;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
html, body{
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}
</style>
