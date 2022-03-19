<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TaskApp msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import TaskApp from './components/TaskApp.vue'

export default {
  name: 'App',
  components: {
    TaskApp
  }
}
</script>


