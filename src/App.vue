<template>
  <div class="flex">
    <Nav />
    <Main />
  </div>
  <Player />
</template>

<script>

import Main from './components/Main.vue'
import Nav from './components/Nav.vue'
import Player from './components/Player.vue'


export default{
  components: {
    Main,
    Nav,
    Player
  }
}

</script>

<style scoped>

</style>