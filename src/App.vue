<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
    <div class="test">呵呵</div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="sass">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.test{
  width: 100px;
}

</style>
