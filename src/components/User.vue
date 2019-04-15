<template>
    <div class="user">
        <p><b>Olá, {{user}}! </b><br>
        Você está agora em um posto participante da rede+ </p>
        <button>Pague pelo APP</button>
        <p id="info">
            Efetue o pagamento on-line pelo app e acumule seus pontos automaticamente.
        </p>
        <a href="#">Saiba aqui como pagar.</a>
    </div>
</template>

<script>
export default {
  name: 'User',
   props: {
    user: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    
    .user{
        margin-top: 1em;
        background-color: white;
        background-image: url('../assets/BG home.png');
        height: 102px;  
        font-size: 13pt;
        
    }
    p{
        text-align: left;
        padding-top: 1em;
        margin-left: 1em;
    }
    button{
        background-color: gray ;
        border: none;
        border-radius: 5px;
        color: white;
        padding: 0.8em 4em;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 13pt;
        margin-top: 1em ;
        cursor: pointer;
        text-transform: uppercase;
        font-weight: bold;
        
    }
    #info{
        margin: 0 5%;
        color: gray;
        text-align: center;
        font-size: 10pt;
        font-weight: bold;
    }
    a {
        font-size: 10pt;
        font-weight: bold;
        color:goldenrod;
    }
</style>
