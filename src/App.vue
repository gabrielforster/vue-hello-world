<template>
  <HeaderComponent />
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <BodyComponent />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderComponent from './components/Header.vue'
import BodyComponent from './components/Body.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    HeaderComponent,
    BodyComponent
  }
}
</script>

<style>

*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
