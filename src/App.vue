<template>
  <div id="app">
    <Portifolio/>
    <Header/>
  </div>
</template>

<script>
import Portifolio from './main/Portifolio'
import Header from './components/Header'


export default {
  name: 'App',
  components: {
    Portifolio,
    Header
  }
}
</script>

<style>
#app {

  
}
</style>
