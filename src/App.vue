<template>
  <div id="app">
    <router-view></router-view>
    <mainTabBar></mainTabBar>
  </div>
</template>

<script>
  import mainTabBar from 'components/content/mainTabbar/MainTabBar'
  export default {
    name: 'app',
    components: {
      mainTabBar
    }
  }
</script>

<style>
@import url('./assets/css/base.css');
</style>
