<template>
  <Header />
  <Menu />
  <Migas />
  <Descripcion />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'
import Migas from './components/Migas.vue'
import Descripcion from './components/Descripcion.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header, Menu, Migas,
    Descripcion, Footer

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(32, 31, 31);
  margin: 0;
}

body {
  margin: 0;
}
</style>
