<template>
  <div id="app">
    <header>
      <app-header/>
    </header>
   
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'


export default {
  name: 'App',
  components: {
    AppHeader,
  }
}
</script>

<style lang="scss">
@import './styles/general.scss';
</style>
