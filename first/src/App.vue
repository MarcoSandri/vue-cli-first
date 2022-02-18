<template>
  <div id="app">
    <TitleComponent></TitleComponent>
    <HeroComponent></HeroComponent>
  </div>
</template>

<script>
import TitleComponent from './components/TitleComponent.vue'
import HeroComponent from './components/HeroComponent.vue'

export default {
  name: 'App',
  components: {
    TitleComponent,
    HeroComponent
  }
}
</script>

<style lang="scss">
body {
  margin:0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0080ff;
  margin-top: 60px;
}
</style>
