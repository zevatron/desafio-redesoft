<template>
    <nav class="footer">
        <ul>
            <li>
                <img src="../assets/Icon home.svg" alt="">
                <p>home</p>
            </li>
            <li>
                <img src="../assets/Icon promocoes.svg" alt="">
                <p>postos</p>
            </li>
            <li>
                <img src="../assets/Icon postos.svg" alt="">
                <p>postos</p>
            </li>
            <li>
                <img src="../assets/Icon extrato.svg" alt="">
                <p>extrato</p>
            </li>
        </ul>
        
    </nav>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .footer{
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        color:#333333;
    }
    p{
        margin: 0;
        font-size: 10px;
    }
    
    ul{
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color:gainsboro ;
    }
    li{
        display: inline-block;
        margin-top:0.5em;
        padding: 0 0.7em;
    }
    
</style>
