<template>
  <div id="app">
    <MainTitle />
  </div>
</template>

<script>
import MainTitle from './components/Title.vue'

export default {
  name: 'App',
  components: {
    MainTitle
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
