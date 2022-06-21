<template>
  <div id="app">
    <MainTitle/>
    <HeroImage/>
  </div>
  
</template>

<script>
import MainTitle from './components/MainTitle.vue'
import HeroImage from './components/HeroImage.vue'
export default {
  name: 'App',
  components: {
    MainTitle,
    HeroImage
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: antiquewhite;
}
</style>
