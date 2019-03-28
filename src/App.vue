<template>
  <v-app>
    <Menu/>
    <HelloWorld/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Menu from './components/Menu.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Menu
  }
}
</script>

<style scoped>
  #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #123e50;
  }
</style>
