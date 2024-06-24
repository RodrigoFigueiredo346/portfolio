<template>
  <HomePage msg="Bem vindo ao meu portfólio" />
</template>

<script>
  import HomePage from './pages/HomePage.vue'

  export default {
    name: 'App',
    components: {
      HomePage
    }
  }
</script>

<style>
  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin: 0;
    /* Remove any default margin */
    padding: 0;
    /* Remove any default padding */
  }
</style>
