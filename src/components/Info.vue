<template>
    <div class="info">
        <NavBar />
        <p>
            O pit stop onde você<br>ganha pontos e<br>muito mais!
        </p>
    </div>
</template>

<script>
import NavBar from './NavBar'

export default {
  name: 'Info',
  components:{
      NavBar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .info{
        height: 40vmax;
        background-image: linear-gradient(to bottom, rgba(0,0,0,0.6) 0%,rgba(0,0,0,0.6) 100%) , url('../assets/posto.jpg');
        background-repeat:no-repeat;
        background-size:cover;
        background-position:center;
    }
    p{
        text-align: right;
        border-top: 2px solid;
        border-bottom: 2px solid;
        margin: 0.5em 0.5em;
        padding: 1em 1em;
        font-size: 1.5em;
        

    }

</style>
