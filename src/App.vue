<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'
  import Component from 'vue-class-component'

  @Component
  export default class App extends Vue {
  }
</script>

<style lang="scss">
  @import "../node_modules/vuetify/dist/vuetify.min.css";
</style>
