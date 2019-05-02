<template>
  <div id="app">
    <MainHeader />
    <MainCarousel />
    <ServiceSection />
    <ProductSection />
  </div>
</template>

<script>
  import MainHeader from './components/MainHeader.vue'
  import MainCarousel from './components/MainCarousel.vue'
  import ServiceSection from './components/ServiceSection.vue'
  import ProductSection from './components/ProductSection.vue'

  export default {
    components: {
      MainHeader,
      MainCarousel,
      ServiceSection,
      ProductSection
    }
  }
</script>

<style lang="sass">
  @import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro")
  @import "./assets/scss/common"
</style>