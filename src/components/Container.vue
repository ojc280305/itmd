<template>
  <div>
    <Navigation/>
    <Vote name="hsdfjkl" image="www.image.com" description="fdsa"/>
  </div>
</template>

<script>
  import Navigation from '@/components/Navigation'
  import Vote from '@/components/Vote'

  export default {
    name: 'container',
    template: '<Container/>',
    components: {
      Navigation,
      Vote
    }
  }
</script>

<style scoped>
  div{
    margin: 20px auto;
    width: 60%;
    min-height: 500px;
    background-color: #eee;
  }
</style>
