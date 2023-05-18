<template>  
  <router-view/>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Orbitron&display=swap');

* {
  box-sizing: border-box;
}
body {
  margin: 0px !important;
}
#app {
  font-family: 'Orbitron', sans-serif;
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #000000;
  color: white;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
