<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <Example />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Example from './components/Example.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Example
  }
}
</script>
