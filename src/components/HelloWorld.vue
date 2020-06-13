<template>
  <div class="login-panel">
    <h1 class="login-panel__title">Welcome to web-game</h1>
    <div class="login-panel__login-form">
        <form action="POST">
            <label for="username">Username:</label>
            <input name="username" type="text">

            <label for="password">Password:</label>
            <input type="password">
        </form>
    </div>
    <div class="login-panel__register-form">
        <form action="">
            
        </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: red;
}
</style>