<template>
  <div id="app">
    <Container/>
  </div>
</template>

<script>
import Container from '@/components/Container'

export default {
  name: 'App',
  components: {
    Container
  }
}
</script>

<style>
#app {
  font-family: 'Impact', 'Arial Black', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000;
  margin-top: 60px;
}
</style>
