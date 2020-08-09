<template>
  <div id="app">
    <Container />
  </div>
</template>

<script>
import Container from './components/Container.vue'

export default {
  name: 'App',
  components: {
    Container
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  line-height: 1.4;
  text-align: center;
}

h1 {
  color: black;
  font-family: 'Rajdhani', sans-serif;
}
</style>
