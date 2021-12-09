<template>
  <div id="app">

    <Header />

  </div>
</template>

<script>
import Header from './components/Header.vue'


export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">
#app {
    font-family: 'Cabin', sans-serif;
    font-family: 'Cabin Sketch', cursive;
    font-family: 'Outfit', sans-serif;
    font-family: 'Readex Pro', sans-serif;

}
</style>
