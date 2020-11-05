<template>
  <div >
    <p class="badNews">{{ msg }}</p>
    <div>
    <p class="message">
      the page you are looking for might be removed or is temporarily unavailable
    </p>
    </div>
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
.badNews{
position: absolute;
width: 586px;
height: 190px;
left: 735px;
top: 265px;
font-family: "Space Mono";
font-style: normal;
font-weight: bold;
font-size: 64px;
line-height: 95px;
letter-spacing: -0.035em;
color: #333333;
}
.message{
position: absolute;
width: 381px;
height: 108px;
left: 736px;
top: 491px;
font-family: "Space Mono";
font-style: normal;
font-weight: normal;
font-size: 24px;
line-height: 36px;
letter-spacing: -0.035em;
}

</style>
