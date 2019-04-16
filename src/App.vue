<template>
  <div id="app">
    <Info />
    <User user="Fernanda" />
    <Footer />
    
  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import Info from './components/Info.vue'
import User from './components/User.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Info,
    User,
    Footer
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  border:0;
}
#app {
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}
</style>
