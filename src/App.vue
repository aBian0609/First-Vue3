<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Header class="header" msg="Welcome to Your Vue.js App [Header components]"/>
  <div class="artice">
    <Left class="artice-left" msg="Welcome to Your Vue.js App [Left components]"/>
    <Right class="artice-right" msg="Welcome to Your Vue.js App [Right components]"/>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Left from './components/Left.vue'
import Right from './components/Right.vue'

export default {
  name: 'App',
  components: {
    Header,
    Left,
    Right,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.artice{
    background-color: #f1f1f1;
    display: flex;
    justify-content: center;

}
</style>
