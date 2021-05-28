<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Title/>
    <Hero/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Title from './components/Title'
import Hero from './components/Hero'

export default {
  name: 'App',
  components: {
    // HelloWorld
    Title,
    Hero
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
  width: 100%;
  height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #15243c;
  color: white;
}

img {
  width: 100px;
}
</style>
