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
        margin: 0px;
    }
    div{
        /* height: 50vmax; */
    }
    image,img{
        float: left;

        padding: 2em;
    }
    p{
        padding-top: 1em;
        text-align: right;
        font-size: 2em;
        margin-right: 1em;
        
    }

</style>
