<template>
  <div id="app">
    <header>
      <app-header/>
    </header>
    <main>
      <section>
        <app-jumbotron/>

      </section>
    </main>
   
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppJumbotron from './components/AppJumbotron.vue'


export default {
  name: 'App',
  components: {
    AppHeader,
    AppJumbotron,
  }
}
</script>

<style lang="scss">
@import './styles/general.scss';
</style>
