<template>
  <div id="app">
    <MainTitle />
    <MainJumbo />
  </div>
</template>

<script>
import MainTitle from './components/Title.vue' ;
import MainJumbo from './components/Banner.vue' ;

export default {
  name: 'App',
  components: {
    MainTitle,
    MainJumbo
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
