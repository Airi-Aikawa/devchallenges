<template>
  <div>
    <header class="headerpc">{{ header }}</header>
    <header class="headersp">{{ header }}</header>
    <div id="img">
      <img alt="Scarecrow" src="./assets/Scarecrow.png" class="imgpc" />
      <img alt="Scarecrow" src="./assets/Scarecrow.png" class="imgsp" />
    </div>
    <HelloWorld msg="I have bad news for you" />
    <button class="buttonpc">BACK TO HOMEPAGE</button>
    <button class="buttonsp">BACK TO HOMEPAGE</button>
    <footer class="footerpc">{{ footer }}</footer>
    <footer class="footersp">{{ footer }}</footer>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  data: function () {
    return {
      header: "404 NOT FOUND",
      footer: "Your name @ DevChallenge.io",
    };
  },
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style scoped>
.headerpc {
  display: block !important;
}
.headersp {
  display: none !important;
}
@media only screen and (max-width: 961px) {
  .headerpc {
    color: #333333;
    position: absolute;
    width: 200px;
    height: 25px;
    left: 77px;
    top: 40px;
    font-family: "Inconsolata";
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 25px;
    letter-spacing: -0.08em;
    text-transform: uppercase;
  }
}
@media screen and (min-width: 375px) {
  .headersp {
    position: absolute;
    width: 133px;
    height: 25px;
    left: 24px;
    top: 20px;
    font-family: Inconsolata;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 25px;
    letter-spacing: -0.08em;
    text-transform: uppercase;
    color: #333333;
  }
}
.buttonpc {
  display: block !important;
}
.buttonsp {
  display: none !important;
}
@media only screen and (max-width: 961px) {
  .buttonpc {
    color: #ffffff;
    size: 14px;
    position: absolute;
    width: 216px;
    height: 68px;
    left: 740px;
    top: 663px;
    background: #333333;
  }
}
@media screen and (min-width: 375px) {
  .buttonsp {
    color: #ffffff;
    size: 14px;
    position: absolute;
    width: 216px;
    height: 68px;
    left: 24px;
    top: 726px;
    background: #333333;
  }
}
.imgpc {
  display: block !important;
}
.imgsp {
  display: none !important;
}

@media only screen and (max-width: 961px) {
  .imgpc {
    width: 539.22px;
    height: 414.25px;
    top: 265px;
    left: 77px;
    position: relative;
  }
}
@media screen and (min-width: 375px) {
  .imgsp {
    width: 286.83px;
    height: 220.35px;
    top: 109px;
    left: 44px;
  }
}
.footerpc {
  display: block !important;
}
.footersp {
  display: none !important;
}

@media only screen and (max-width: 961px) {
  .footerpc {
    position: absolute;
    width: 226px;
    height: 17px;
    left: 607px;
    top: 1024px;
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #333333;
  }
}
@media screen and (min-width: 375px) {
  .footersp {
    position: absolute;
    width: 226px;
    height: 17px;
    left: 75px;
    top: 890px;
    font-family: Montserrat;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #333333;
  }
}
</style>
