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
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body{
  background-color: rgb(155, 247, 162);
}
</style>
