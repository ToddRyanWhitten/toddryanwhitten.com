<template>
  <HelloWorld msg="toddryanwhitten.com"/>
  <IndexMenu menuItem="Please enjoy.."></IndexMenu>
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
