<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Carousel />
    <Home />
  </div>
</template>

<script>
  import Home from './components/Home.vue'
  import Carousel from './components/Carousel.vue'

  export default {
    name: 'app',
    components: {
      Home,
      Carousel
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>