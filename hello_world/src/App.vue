<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Title_1 msg="La mia prima app con Vue CLI"/>
  </div>
</template>

<script>
import Title_1 from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Title_1
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
