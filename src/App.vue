<template>
  <div id="app">
    <Header></Header>
    <About></About>
    <Portfolio></Portfolio>
    <Works></Works>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Portfolio from './components/Portfolio.vue'
import Works from './components/Works.vue'

export default {
  name: 'App',
  components: {
    Header,
    About,
    Portfolio,
    Works
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Saira+Stencil+One&display=swap');

body {
  background-color: #e0ffff;
}
#app {
  font-family: 'Kiwi Maru';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
