<template>
  <div id="app" class="p-2 w-screen h-screen bg-yellow-300 flex justify-center items-center">
      <DropDownList msg="Welcome to Your beautiful dropdown list"/>
  </div>
</template>

<script>
import DropDownList from './components/DropDownList.vue'

export default {
  name: 'App',
  components: {
    DropDownList
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
