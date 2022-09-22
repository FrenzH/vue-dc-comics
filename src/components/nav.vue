<template>
  <div>
    <nav>
      <a href="">CHARACTERS</a>
      <a href="">COMICS</a>
      <a href="">MOVIES</a>
      <a href="">Tv</a>
      <a href="">GAMES</a>
      <a href="">COLLECTIBLES</a>
      <a href="">VIDEOS</a>
      <a href="">FANS</a>
      <a href="">NEWS</a>
      <a href="">SHOP</a>


    </nav>

  </div>
</template>

<script>
export default {
    name:'navComponent'

}
</script>

<style lang="scss" scoped>

    nav{
        display: flex;
        a{
          text-decoration: none;
          padding: 20px 10px;
          color:black;
        }
        a:hover{
          border-bottom: 2px black solid;
        }
        
    }

</style>