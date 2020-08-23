<template>
  <div id="app">
    <BaseNav></BaseNav>
    <router-view/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import BaseNav from './components/BaseNav.vue'

export default Vue.extend({
  name:'App',
  components:{BaseNav}
})
</script>
<style>

body{
  margin: 0 !important;
  padding: 0 !important;
}

#app {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
