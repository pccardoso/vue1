<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <p>Olá meu projeto versionado GitHub</p>

  <ComponenteTeste @update-message="emitirAlert"/>

</template>

<script>

  import ComponenteTeste from "./components/ComponenteTeste.vue"

  export default {
    name: 'App',
    components: {
      ComponenteTeste
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
