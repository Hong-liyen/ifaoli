<template>
  <div id="app">
    <Header/>
    <Slick/>
    <Tab/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Slick from './components/Slick.vue'
import Tab from './components/Tab.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Header,
    Slick,
    Tab,
    Footer
  }
}
</script>

<style lang="scss">

</style>
