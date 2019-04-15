<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <NavBar/>
    <Info msg="O pit stop onde você ganha pontos e muito mais!" />
    <User user="Fernanda" />
    <Footer />
    
  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import NavBar from './components/NavBar.vue'
import Info from './components/Info.vue'
import User from './components/User.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    NavBar,
    Info,
    User,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 0px;
  background-color: #2c3e50;
}
</style>
