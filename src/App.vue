<template>
  <img alt="Vue logo" src="./assets/tiger.jpg" style="width: 50vw;">
  <img alt="Vue logo" src="./assets/sq.jpg" style="width: 50vw;">
  <HelloWorld msg="Welcome to My Portfolio"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
