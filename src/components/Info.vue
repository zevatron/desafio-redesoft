<template>
    <div class="info">
        <p> {{msg}} </p>
    </div>
</template>

<script>
export default {
  name: 'Info',
   props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .info{
        margin: 1em;
    }
    p{
        font-size: 2em;
        text-align: right;
        border-top-style: solid;
        border-bottom-style: solid;
    }

</style>
