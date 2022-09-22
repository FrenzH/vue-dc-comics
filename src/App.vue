<template>
  <div id="app">
    
    <headerComponent/>
    <mainComponent/>
    <utilsLinkComponent/>
    
  </div>
</template>

<script>

import headerComponent from './components/header.vue';
import mainComponent from './components/main.vue';
import utilsLinkComponent from './components/utilsLink.vue';

export default {
  name: 'App',
  components: {
    headerComponent,
    mainComponent,
    utilsLinkComponent
    
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  
  
  
}
</style>
