<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">MeatDevs</router-link> |
      <router-link to="/about">About</router-link> | 
      <a href="https://mailchi.mp/7fd00f8f4f23/meatdevs">Newsletter</a>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    font-size: 1.5em;
    color: white;
    &.router-link-exact-active {
      color: red;
    }
  }
}
</style>
