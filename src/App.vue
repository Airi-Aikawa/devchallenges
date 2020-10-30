<template>

  <div id="img">
    <p>{{title}}</p>
    <img alt="Scarecrow" src="./assets/Scarecrow.png">
    <HelloWorld msg="I have bad news for you"/>
    <button>BACK TO HOMEPAGE</button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  data:function(){
    return{
      title:'404 NOT FOUND'
    }
  },
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  /* position: absolute; */
width: 216px;
height: 68px;
left: 740px;
  margin-top: 663px;
}
</style>
