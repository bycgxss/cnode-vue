<template>
  <div id="app">
    <Header></Header>
  </div>
</template>

<script>
  import Header from './components/Header'
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
  #app {
    background: #e1e1e1;
  }
  .main {
    width: 90%;
    margin: 0 auto;
  }
</style>
