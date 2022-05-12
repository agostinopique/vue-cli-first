<template>

  <div id="app">
    <TitleEl />
    <HeroEl />
  </div>

</template>

<script>

import TitleEl from './components/TitleEl.vue'
import HeroEl from './components/HeroEl.vue'


export default {
  name: "App",
  components: {
    TitleEl,
    HeroEl
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
