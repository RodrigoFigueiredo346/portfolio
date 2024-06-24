<template>
  <div class="hello">

    <HeaderComponent />
    <h1>{{ msg }}</h1>

  </div>
</template>


<script>

  import HeaderComponent from '../components/HeaderComponent.vue';

  export default {
    name: 'HomePage',
    props: {
      msg: String
    },
    components: {
      HeaderComponent
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h3 {
    margin: 0px 0 0;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
