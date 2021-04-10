<template>
  <div id="app">
      <Header></Header>
      <About></About>
      <Portfolio></Portfolio>
      <Skill></Skill>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Skill from './components/Skill.vue'
import Portfolio from './components/Portfolio.vue'

export default {
  components: {
    Header,
    About,
    Skill,
    Portfolio
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Saira+Stencil+One&display=swap');

body {
  background-color: #e0ffff;
}
#app {
  /*font-family: Avenir, Helvetica, Arial, sans-serif;*/
  font-family: 'Kiwi Maru';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
