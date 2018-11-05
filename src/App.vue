<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
    <header-wrapper></header-wrapper>
    <main-container></main-container>

  </div>
</template>

<script>
export default {
  components: {
    HeaderWrapper: () => import('./components/HeaderWrapper'),
    MainContainer: () => import('./components/MainContainer'),
  }
}
</script>


<style>
#app {
  padding: 0;
  margin: 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
