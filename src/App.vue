<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <lorem-ipsum/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import LoremIpsum from "./components/LoremIpsum";

export default {
  name: 'App',
  components: {
    LoremIpsum,
    HelloWorld
  }
}
</script>

<style>
body{
  padding-top: env(safe-area-inset-top);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
