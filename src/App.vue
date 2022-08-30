<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'lv-tarefas',
  data(){
    return{
      titulo: 'Listagem de tarefas',
      subtitulo: 'Defina uma descrição',
      tarefas: []
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
