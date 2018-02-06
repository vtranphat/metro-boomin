<template>
  <div id="app">
    <headers></headers>
    <home></home>
    <footers></footers>
    <router-view/>
  </div>
</template>

<script>
import headers from '@/components/header/header';
import footers from '@/components/footer/footer';
import home from '@/components/home/home';
export default {
  name: 'App',
    components: {
    headers,
    footers,
    home
  },
}
</script>

<style>
body {
  padding : 0;
  margin :0;
}
#app {
  
  font-family: 'proxima nova', "avenir", Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
