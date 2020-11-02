<template>
  <div id="header">
    <header>{{title}}</header>
    <div id = "img">
    <img alt="Scarecrow" src="./assets/Scarecrow.png" class="img">
    </div>
    <HelloWorld msg="I have bad news for you"/>
    <button class= "button button-close">BACK TO HOMEPAGE</button>
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

<style scoped>
#app {
  /* position: absolute; */
width: 216px;
height: 68px;
left: 740px;
  margin-top: 663px;
}
.button{
  color: FFFFFF;
  Size :14px;
    position: absolute;
width: 216px;
height: 68px;
left: 740px;
top: 663px;
background: #333333;
}
.img{
  Width :539.22px;
Height: 414.25px;
Top :265px;
Left :77px

}
</style>
