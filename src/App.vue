<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png" width="25%" />-->
    <!--<HelloWorld msg="Hello Vue in CodeSandbox!" />-->
    <router-link to="/">Home</router-link> |
    <router-link to="/vmodel">V-Model</router-link> |
    <router-link to="/von">V-On</router-link> |
    <router-link to="/vbind">V-Bind</router-link> |
    <router-link to="/prop">Prop</router-link> |
    <router-link to="/axios">Axios</router-link>
    <br /><br />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.router-link-exact-active {
  color: red;
}
</style>

