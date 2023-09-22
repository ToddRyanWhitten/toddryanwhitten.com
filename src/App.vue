<template>
  <IndexMenu menuItem="Do what you can, with what you have, where you are"></IndexMenu>
  <HelloWorld msg="2023/09/22"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import IndexMenu from './components/IndexMenu.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    IndexMenu
  }
}
</script>

<style>
#app { }
</style>
