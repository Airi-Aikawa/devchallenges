<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      the page you are looking for might be removed or is temporarily unavailable
    </p>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
