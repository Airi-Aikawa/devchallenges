<template>
  <div>
    <header class="header">{{title}}</header>
    <div id = "img">
    <img alt="Scarecrow" src="./assets/Scarecrow.png" class="img">
    </div>
    <HelloWorld msg="I have bad news for you"/>
    <button class= "button button-close">BACK TO HOMEPAGE</button>
    <footer class="footer">Your name @ DevChallenge.io</footer>
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
.header{
color: #333333;
position: absolute;
width: 200px;
height: 25px;
left: 77px;
top: 40px;
font-family: Inconsolata;
font-style: normal;
font-weight: bold;
font-size: 24px;
line-height: 25px;
letter-spacing: -0.08em;
text-transform: uppercase;
}
.button{
color: #FFFFFF;
Size :14px;
position: absolute;
width: 216px;
height: 68px;
left: 740px;
top: 563px;
background: #333333;
}
.img{
Width :539.22px;
Height: 414.25px;
Top :265px;
Left :77px;
position: absolute;
left: 5.35%;
right: 57.21%;
top: 24.54%;
bottom: 37.11%;
}
.footer{
position: absolute;
width: 226px;
height: 17px;
left: 607px;
top: 1024px;
font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 14px;
line-height: 17px;
/* identical to box height */


color: #333333;
}
</style>
