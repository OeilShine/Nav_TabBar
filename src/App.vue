<template>
  <div id="app" class="wrapper">
    <router-view/>
    <main-tab-bar/>
  </div>
</template>

<script>
  import MainTabBar from './components/mainTabbar/MainTabBar'

  export default {
    name: 'app',
    components: {
      MainTabBar
    }
  }
</script>

<style>
  @import "./assets/css/base.css";
</style>
