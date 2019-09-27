<template>
  <div id="app">
    <Calander />
  </div>
</template>

<script>
import Calander from './components/Calander.vue'

export default {
  components: {
    Calander
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
