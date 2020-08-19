<template>
  <div id="app">
    <SampleApp />
  </div>
</template>

<script>
import SampleApp from './components/SampleApp.vue'

export default {
  name: 'App',
  components: {
    SampleApp
  }
}
</script>

<style>
  @import './assets/styles/global.css';
</style>
