<template>
<header>
<div class="headerClass">
  <div class="logo">
      <img src="../assets/logo.png" alt="Vue Logo">
      <h3>Vue Header</h3>
  </div>
  <div class="menu">
      <a
      href="https://github.com/gabrielforster"
      target="_blank">My Github</a>

      <!-- <a
      href="https://github.com/gabrielforster/vue-hello-world"
      target="_blank">This repo on Github</a> -->
  </div>
</div>
</header>
</template>

<script>

export default {
    name: 'HeaderComponent'
}

</script>

<style scoped lang='scss' src='../assets/styles/App.scss' />
