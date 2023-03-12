<template>
  <div id="app">
<Headers></Headers>
<router-view></router-view>
<Footer></Footer>
  </div>
</template>

<script>
import Headers from './components/Header/index.vue'
import Footer from './components/Footer/index.vue'
export default {
  name: 'App',
  components: {
    Headers,
    Footer
  }
}
</script>

<style>

</style>
