<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <womp msg="Yeah let's try this"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import womp from './components/womp.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    womp
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
