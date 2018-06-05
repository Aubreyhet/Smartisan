<template>
  <div id="app">
    <headerNav></headerNav>
    <shops></shops>
    <router-view></router-view>
  </div>
</template>

<script>
import headerNav from './components/header-nav';
import shops from './views/shop';
export default {
  name: 'app',
  components :{
    headerNav,
    shops
  }
}

</script>

<style>
</style>
