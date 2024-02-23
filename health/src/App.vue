

<template>
  
  <NavBar/>

  <router-view/>

</template>

<script>

import NavBar from './components/NavBar.vue';
export default{
  components:{
    NavBar,
    NavBar
}
}
</script>

<style>
#app {
  font-family: 'Maven Pro', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: transparent;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
