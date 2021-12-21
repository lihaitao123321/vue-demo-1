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
      <div class="content">
        <div class="title">tms运输管理系统</div>
        <div class="text1">
          <div class="input-warp">
            <input />
          </div>
        </div>
        <div class="text2">
          <div class="input-warp">
            <input />
          </div>
          <div class="icon-warp">
            <img src="./assets/eye-close.png" />
            <!-- <img :src="require('./assets/eye-close.png')" /> -->
          </div>
        </div>
        <div class="button">登录</div>
      </div>
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
  /* 纵向排列 */
  flex-direction: column;
  /* align-items: center; */
  justify-content: center;
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
.login-container {
  display: flex;
  justify-content: flex-end;
  width: 100%;
}
.content {
  width: 500px;
  height: 400px;
  background-color: white;
  margin-right: 200px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.title {
  font-size: 24px;
  font-weight: bold;
  color: green;
}
.text1,
.text2 {
  /* 布局 */
  width: 400px;
  height: 50px;
  margin-top: 40px;
  /* 装饰 */
  /* background-color: gray; */
  display: flex;
  align-items: center;
  border-bottom: 1px solid rgba(0, 0, 0, 0.3);
}
.input-warp {
  width: 0;
  height: 50px;
  flex-grow: 1;
}
.input-warp input {
  width: 95%;
  height: 95%;
  border: none;
  outline: none;
  padding-left: 10px;
}
.icon-warp {
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.icon-warp img {
  width: 35px;
  height: 20px;
}
.button {
  width: 300px;
  height: 50px;
  margin-top: 40px;
  background-color: rgb(35, 139, 251);
  color: white;
  /* 鼠标放上去变成手 */
  cursor: pointer;
  /* 下main三个可实现剧中效果 */
  display: flex;
  align-items: center;
  justify-content: center;
  /* 圆角 */
  border-radius: 25px;
}
</style>
