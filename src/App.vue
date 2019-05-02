<template>
  <div id="app">
    <MainHeader />
    <MainCarousel />
  </div>
</template>

<script>
  import MainHeader from './components/MainHeader.vue'
  import MainCarousel from './components/MainCarousel.vue'

  export default {
    components: {
      MainHeader,
      MainCarousel
    }
  }
</script>

<style lang="sass">
  @import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro")
  @import "./assets/scss/common"
</style>
