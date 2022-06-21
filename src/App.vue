<template>
  <div id="app">
    <TheHeader></TheHeader>
    <TheContent></TheContent>
    <BlueBanner></BlueBanner>
    <MainFooter></MainFooter>
  </div>
</template>

<script>

import TheHeader from './components/TheHeader.vue'
import TheContent from './components/TheContent.vue'
import BlueBanner from './components/BlueBanner.vue'
import MainFooter from './components/MainFooter.vue'
export default {
  name: 'App',
  components: {
    TheHeader,
    TheContent,
    BlueBanner,
    MainFooter
    
  }
}
</script>

<style lang="scss">
@import url(../node_modules/bootstrap);
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  
  ;
}
</style>
