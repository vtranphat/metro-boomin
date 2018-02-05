<template>
  <div id="app">
    <headers></headers>
    <footers></footers>
    <router-view/>
  </div>
</template>

<script>
import headers from '@/components/header/header';
import footers from '@/components/footer/footer'
export default {
  name: 'App',
    components: {
    headers,
    footers
  },
}
</script>

<style>
#app {
  
  font-family: 'proxima nova', "avenir", Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
