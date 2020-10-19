<template>
  <div id='text'>
    {{text}}
  </div>
</template>

<script>
  export default {
    data() {
      return {
        text: 'salted fish'
      }
    },
  }
</script>

<style scoped>
 #text{
   color:red;
 }
</style>