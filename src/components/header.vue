<template>
  <div>
    <img src="../assets/img/dc-logo.png" alt="">
    <navComponent/>
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

<style scoped>

</style>