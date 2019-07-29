<template>
  <div id="app">
       <GradebookApp msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import GradebookApp from './components/GradebookApp.vue'

export default {
  name: 'app',
  components: {
    GradebookApp
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
 }
</style>
