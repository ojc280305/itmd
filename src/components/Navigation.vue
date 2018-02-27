<template>
  <div>
    <ul>
      <li>All</li>
      <li>List</li>
      <li>Submit</li>
    </ul><hr>
  </div>
</template>

<script>
export default {
  name: 'navigation',
  template: '<Navigation/>'
}
</script>

<style scoped>
  ul {

    height: 25px;
    font-size: 20px;
    font-weight:bold;
    text-transform:uppercase;
    list-style-type: none;
    position: relative;
  }
  li{
    height: 25px;
    top:30%;
    bottom: 40%;
    display: inline-block;
    position: relative;
    margin-right: 15px;
    left:0;
    right:0;
  }
</style>
