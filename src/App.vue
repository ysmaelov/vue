<template>
  <div id="app">
    <div id="menu">
      <MenuSidebar></MenuSidebar>
    </div>
    <div id ="main">
      <router-view/>
    </div>
  </div>
</template>

<script>
  import MenuSidebar from './components/MenuSidebar.vue'
  import HelloWorld from "./components/HelloWorld";
  import GridLayouts from "./components/GridLayouts"
export default {
  name: 'App',
  components:{HelloWorld, MenuSidebar,GridLayouts}
}
</script>

<style>
  #app{
    padding-left: 350px;
  }
#menu{
  width: 178px;
  height: 100%;
  float:left;}
  #main{
  }
</style>
