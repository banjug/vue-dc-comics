<template>
  <div id="app">
    <Header/>
    <Main/>
    <LinkStrip/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import LinkStrip from './components/LinkStrip.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    LinkStrip,
  }
}
</script>

<style lang="scss">

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
  // margin-top: 60px;
}
</style>
