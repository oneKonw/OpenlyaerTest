<template>
  <div id="app">
    <MapPage />
  </div>
</template>

<script>
import MapPage from './page/Map.vue'

export default {
  name: 'App',
  components: {
    MapPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  height: 100vh;
}

* {
  margin: 0;
  padding: 0;
}
</style>
