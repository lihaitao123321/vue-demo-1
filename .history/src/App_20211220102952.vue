<template>
  <div id="app">
    <!-- <div class="div1">
      111
    </div> -->
    <!-- <div class="div2">
      222
    </div>
    <div class="div3">
      333
    </div> -->
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <div class="login-container">

    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
}
#app {
  background-color: gray;
  height: 100vh;
  display: flex;
  /*flex-direction: column;纵向排列 */
  /* align-items: center; */
  /* justify-content: center; */
}
.div1 {
  background-color: red;
  width: 200px;
}
.div2 {
  background-color: green;
  width: 0;
  flex-grow: 1;
}
.div3 {
  background-color: red;
  width: 200px;
}
</style>
