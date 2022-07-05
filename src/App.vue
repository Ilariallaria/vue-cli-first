<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle msg="La mia prima app con Vue CLI!"/>
    <MyHero/>
    <MyTitle2/>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyHero from './components/MyHero.vue'
import MyTitle2 from './components/MyTitle2.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero,
    MyTitle2
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
