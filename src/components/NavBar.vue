<template>
    <div class="navbar">
        <img src="../assets/Icon menu.svg" alt="menu">
        <p>rede+</p>
    </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    *{
        margin: 0;
        padding: 0;
    }
    image,img{
        float: left;
        padding: 1em;
    }
    p{
        padding-top: 1em;
        text-align: right;
        font-size: 20px;
        margin-right: 1em;
        
    }

</style>
