<template>
  <MainHeader headerText="header label" />
  <Main />
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    Main
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
  margin: 0;
}
body {
  margin: 0;
  padding: 0;
}
</style>
