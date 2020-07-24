<template>
<div class="home">

  <!--menu-->
  <div class='circle-container'>
    <div class='circle-container'>
      <a href='#' class='center'><img src="../assets/logo.png"></a>
      <a href='#' class='deg2'><img src="https://www.onlygfx.com/wp-content/uploads/2017/11/grunge-circle-frame-6.png"></a>
      <a href='#' class='deg3'><img src="https://www.onlygfx.com/wp-content/uploads/2017/11/grunge-circle-frame-6.png"></a>
      <a href='#' class='deg4'><img src="https://www.onlygfx.com/wp-content/uploads/2017/11/grunge-circle-frame-6.png"></a>
      <a href='#' class='deg5'><img src="https://www.onlygfx.com/wp-content/uploads/2017/11/grunge-circle-frame-6.png"></a>
      <a href='#' class='deg6'><img src="https://www.onlygfx.com/wp-content/uploads/2017/11/grunge-circle-frame-6.png"></a>
      <a href='#' class='deg1'><img src="https://www.onlygfx.com/wp-content/uploads/2017/11/grunge-circle-frame-6.png"></a>
    </div>
    <!-- <div class="CircleButton d-flex align-items-center justify-content-center text-uppercase font-weight-bold">
      <router-link to="/">Home</router-link>
    </div> -->
  </div>
  <!--
    <div class="CircleButton d-flex align-items-center justify-content-center text-uppercase font-weight-bold">
      <router-link to="/about">About</router-link>
    </div>-->
  <!--logo
  <div class="logo">
    <a href='#' class='center'><img alt="logo" src="../assets/logo.png"></a>
  </div>-->
</div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style>
@import '../assets/css/mystyle.css';

/* .CircleButton {
  background: lightblue;
  border-radius: 50%;
  width: 200px;
  height: 200px;
} */

.circle-container {
  position: relative;
  width: 24em;
  height: 35em;
  padding: 2.8em;
  border-radius: 50%;
  margin: 1.75em auto 0;
}

.circle-container a {
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  width: 4em;
  height: 4em;
  margin: -2em;
}

img {
  border-radius: 400px;
  width: 160px;
}

.center img {}

.deg1 img {
  position: relative;
  top: 170px;
}

.deg2 img {
  position: relative;
  bottom: 170px;
}

.deg3 img {
  position: relative;
  top: 90px;
  left: 170px;
}

.deg4 img {
  position: relative;
  top: 90px;
  right: 170px;
}

.deg5 img {
  position: relative;
  bottom: 90px;
  right: 170px;
}

.deg6 img {
  position: relative;
  bottom: 90px;
  left: 170px;
}
</style>
