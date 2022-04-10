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

<style scoped lang='scss'>
@import url(https://fonts.googleapis.com/css?family=Roboto+Mono:100,200,300,regular,500,600,700,100italic,200italic,300italic,italic,500italic,600italic,700italic);

.headerClass{
    margin-bottom: 2rem;
    padding: 1rem;
    display:flex;
    align-items: center;
    justify-content: space-between;
    background-color: #5fd6a1;

    font-family: Roboto Mono;
}

.logo{
    display: flex;
    justify-content: center;
    align-items: center;

    img{
        margin-right:.25rem;
        max-height: 2.5rem;
    }
}

.menu{
    display: flex;

     a{
        margin-left: 1rem;
        text-decoration: none;
        color: #2c3e50;
        font-weight: bold;
    }
}
</style>