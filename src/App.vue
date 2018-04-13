<template>
  <div id="app">
    <Syllabus/>
  </div>
</template>

<script>
import Syllabus from './components/Syllabus.vue'

export default {
  name: 'app',
  components: {
    Syllabus
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
