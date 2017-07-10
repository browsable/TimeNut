<template>
  <div id="app">
    <HeaderBar/>
    <MapSection/>
    <SearchSection/>
    <!--<router-view></router-view>-->
  </div>
</template>

<script>
  import HeaderBar from './components/HeaderBar';
  import MapSection from './components/MapSection';
  import SearchSection from './components/SearchSection';

  export default {
    name: 'app',
    components: { HeaderBar, MapSection, SearchSection },
  };
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
}
</style>
