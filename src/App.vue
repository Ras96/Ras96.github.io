<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Top</router-link> |
      <router-link to="about">About</router-link> |
      <router-link to="/works">Works</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
* {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background: lemonchiffon;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #005caf;
}
</style>
