<template>
  <div id="app">
    <NavigationBar />
    <!-- <Header /> -->
    <!-- <QuestionBox /> -->
  </div>
</template>

<script>

// import Header from './components/Header.vue'
// import QuestionBox from './components/QuestionBox.vue'
import NavigationBar from './components/NavigationBar.vue'

export default {
  name: 'App',
  components: {
    // Header,
    // QuestionBox,
    NavigationBar
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
