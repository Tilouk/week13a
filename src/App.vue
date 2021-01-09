<template>

  <div id="app">

    <layout-header></layout-header>

    <layout-sidebar></layout-sidebar>

    <layout-footer></layout-footer>

  </div>
</template>

<script>

import LayoutHeader from './components/LayoutHeader.vue'
import LayoutSidebar from './components/LayoutSidebar.vue'
import LayoutFooter from './components/LayoutFooter.vue'

export default {
  name: 'App',
  components: {
      LayoutHeader,
      LayoutSidebar,
      LayoutFooter,

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
