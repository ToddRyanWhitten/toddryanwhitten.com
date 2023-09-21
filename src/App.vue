<template>
  <HelloWorld msg="toddryanwhitten.com"/>
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
