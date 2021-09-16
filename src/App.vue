<template>
  <div id="app" @click="clickAction">
      <p class="ps">Accelerated & hosted by 4EVERLAND</p>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {},
  methods: {
      clickAction(){
          window.location.href = 'https://hosting.4everland.org/#/?invite=R41Y6IPN'
      },
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
    position:fixed;
    top: 0;
    left: 0;
    width:100%;
    height:100%;
    z-index:-10;
    zoom: 1;
    background: url('./assets/bg.jpg');
    background-color: #fff;
    background-repeat: no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    background-position: center 0;
    cursor: pointer;
}
.ps{
    position: fixed;
    bottom: 5%;
    right: 5%;
    font-size: 20px;
    color: #fff;
    font-weight: bolder;
}
</style>
