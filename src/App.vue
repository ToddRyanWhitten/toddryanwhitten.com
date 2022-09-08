<template>
  <!-- <HelloWorld msg="toddryanwhitten.com"/> -->
  <IndexMenu menuItem="Item 1"></IndexMenu>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import IndexMenu from './components/IndexMenu.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    IndexMenu
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
