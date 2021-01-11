<template>
  <div id="app">
    <table-test-page></table-test-page>
  </div>
</template>

<script>
import TableTestPage from './components/TableTestPage'

export default {
  name: 'App',
  components: {
    TableTestPage
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
