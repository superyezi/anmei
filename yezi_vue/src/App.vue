<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <hello></hello>
  </div>
</template>

<script>
import hello from './components/hello'

export default {
  name: 'app',
  components: {
    hello
  }
}
</script>

<style>
*{
  margin: 0;padding: 0px;
}
ul,li{
  list-style: none;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

</style>
