<template>
  <div>
    <h1>{{ name }} hjkfdah</h1>
    <img :src="image" :alt="name"/><br>
    <p>
      {{ description }}
    </p>
  </div>
</template>

<script>
export default {
  name: 'vote',
  props: {
    name: {
      default: 'No memes to vote.'
    },
    image: {
      default: 'http://via.placeholder.com/350?text=Placeholder+Meme'
    },
    description: {
      default: 'lo dfhasjl,gvkfh sjkadfgdfsg dfjsg dgjdsfjkfd gfjodgs kfdsg hfjkdsjk;f dyi kfhd d fhdjkslagh dlgh fk ghkldfs gjfodgdfsaklgnfjldgsdjklg fhaklsg hkdfl gdjlgsdjg dsg   ffhdhkfljdsaghfads ds bfdjklsafgdjks  dasf'
    }
  },
  template: '<Vote/>'
}
</script>

<style scoped>
</style>
