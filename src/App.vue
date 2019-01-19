<template>
<div style="margin: 0px;">
    <my-header></my-header>
    
    <HelloWorld msg="Welcome to Your Vue.js App 6"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import myHeader from "./components/Header.vue";

export default {
  name: 'app',
  components: {
    HelloWorld,
    myHeader
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
