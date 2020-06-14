<template>
  <div id="app">
    <LoginRegister text="Default text"/>
  </div>
</template>

<script>
import LoginRegister from './components/LoginRegister'

export default {
  name: 'App',
  components: {
    LoginRegister
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
