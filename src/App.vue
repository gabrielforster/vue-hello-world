<template>
  <HeaderComponent />
  <BodyComponent />
</template>

<script>
import HeaderComponent from './components/Header.vue'
import BodyComponent from './components/Body.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    BodyComponent
  }
}
</script>

<style src='./assets/styles/App.scss' scoped lang='scss' />
