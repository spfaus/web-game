<template>
    <div class="login-panel">
        <h1 class="login-panel__title">{{ text }}</h1>
        <input type="text" v-model="text">
    </div>
</template>

    <script>
export default {
  name: 'LoginRegister',
  props: {
    text: String
  }
}
</script>
 
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>