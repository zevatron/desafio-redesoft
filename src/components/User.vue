<template>
    <div class="user">
        <div class="user-info">
            <p><b>Olá, {{user}}! </b><br>
        Você está agora em um posto participante da rede+ </p>
        </div>
        
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
        margin-bottom: 60px;
    }
    .user-info{
        background-image: url('../assets/BG home.png');
        background-position-y: 80px;
        min-height: 80px;  
        
    }
    p{
        text-align: left;
        padding-top: 1em;
        margin-left: 1em;
        font-size: 13px;
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
        font-size: 10px;
        margin-top: 3em ;
        cursor: pointer;
        text-transform: uppercase;
        font-weight: bold;
        
    }
    #info{
        margin: 0 5%;
        color: gray;
        text-align: center;
        font-size: 8px;
        font-weight: bold;
    }
    a {
        font-size: 8px;
        font-weight: bold;
        color:goldenrod;
    }
</style>
