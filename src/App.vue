<template>
  <div id="app">
    <router-view></router-view>
    <BackgroundRight />
  </div>
</template>

<script>
export default {
  name: 'App',
  component: {
    BackgroundRight
  }
}
import BackgroundRight from './components/BackgroundRight.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
