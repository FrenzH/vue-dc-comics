<template>
  <div>
    <div id="header-container">
      <img src="../assets/img/dc-logo.png" alt="">
      <navComponent/>
    </div>
   
  </div>
</template>

<script>
import navComponent from './nav.vue'
export default {
name: 'headerComponent',

components : {
    navComponent
}
}
</script>

<style lang="scss" scoped>
  #header-container{
    display: flex;
    justify-content: space-evenly;
  }

</style>