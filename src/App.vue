<template>
  <p>Olá meu projeto versionado GitHub</p>
</template>

<script>

  export default {
    name: 'App',
    components: {
    
    },
    methods:{
      emitirAlert(msg){
        alert(msg)
      }
    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
