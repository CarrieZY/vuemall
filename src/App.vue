<template>
  <div id="app">
    <header-top></header-top>
    <router-view/>
  </div>
</template>

<script>
import headerTop from './components/header/header'
export default {
  name: 'App',
  components:{
    headerTop
  }
}
</script>

<style>
</style>
