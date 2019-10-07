<template>
  <div id="app">
    <div id="header">
      <div id="logo"><img src="./assets/logo.png" alt="logo"></div>
      <div id="title"> <router-link to="/">喵耳朵</router-link></div>
      <div id="menu"><router-link to="/menu">目录</router-link></div>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  #header {
    text-align: left;
    width: 100%;
    font-size: 20px;
  }

  #header *{
    display: inline-block;
  }

  #header a {
    margin-left: 5px;
    text-decoration: none;
    color: #000000;
  }

  #logo {
    width: 30px;
    height: 30px;
    margin-left: 10px;
  }

  #logo img {
    vertical-align: middle;
    width: 100%;
    height: 100%;
  }

</style>
