<template>
  <div id="app">
    <app-header></app-header>
    <app-ninjas></app-ninjas>
    <app-footer></app-footer>
    <!--<img src="./assets/logo.png">
    <router-view/>-->
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Ninjas from './components/Ninjas.vue'

export default {
  name: 'App',
  components: {
    'app-header': Header,
    'app-footer': Footer,
    'app-ninjas': Ninjas
  }
}
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  //margin-top: 60px;
}
</style>
