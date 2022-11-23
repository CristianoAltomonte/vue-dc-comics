<template>
  <div id="app">

    <HeaderComics/>

  </div>
</template>

<script>
import HeaderComics from './components/HeaderComics.vue'


export default {

  name: 'App',

  components: {
    
    HeaderComics,

  }
}
</script>

<style lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
}
</style>
