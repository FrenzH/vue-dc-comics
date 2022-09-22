<template>
  <div id="app">
    
    <headerComponent/>
    
  </div>
</template>

<script>

import headerComponent from './components/header.vue'

export default {
  name: 'App',
  components: {
    headerComponent
    
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}
</style>
