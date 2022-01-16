<template>
  <Header />
  <Menu />
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'


export default {
  name: 'App',
  components: {
    Header, Menu

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin: 0;
}

body {
  margin: 0;
}
</style>
