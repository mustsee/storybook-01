<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <task />
  </div>
</template>

<script>
import Task from './components/Tas.vue'

export default {
  name: 'App',
  components: {
    Task
  }
}
</script>

<style lang="scss">
  @import './index.css'
</style>
