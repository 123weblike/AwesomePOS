<template>
  <div id="app">
    <leftNav></leftNav>
    <div class="main"></div>
    <router-view/>
  </div>
</template>

<script>
  import leftNav from '@/components/common/leftNav'
export default {
  name: 'App',
  components:{
    leftNav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height:100%;
}
  /*.main{
    float: left;
    width: 95%;
    background-color: #EFF2F7;
    height: 100%;
    overflow: auto;
  }*/
</style>
