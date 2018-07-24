<template>
  <div id="app">
    <nav-bar></nav-bar>
    <rockets class="container"></rockets>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar.vue'
import Rockets from '@/views/Rockets.vue'

export default {
  name: 'app',
  components: {
    Rockets,
    NavBar
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
