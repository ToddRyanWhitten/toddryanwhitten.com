<template>
  <HelloWorld msg="Do what you can, with what you have, where you are"/>
  <IndexMenu menuItem="2023-09-21"></IndexMenu>
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
