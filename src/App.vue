<template>
  <div id="app">
    <NewHeader></NewHeader>
    <Header></Header>
    <Body></Body>
   <router-view></router-view>
  </div>
</template>

<script src="./assets/js/echarts"></script>

<script>

import Header from './components/Header.vue'
import NewHeader from './components/NewHeader.vue'
import Body from './components/Body'
export default {
  name: 'App',
  components: {
    Body,
    Header,
    NewHeader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;

} 
body{
  margin: 0;
}
        
        
        
    
</style>  
