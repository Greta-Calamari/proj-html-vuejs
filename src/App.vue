<template>
  <div id="app">
    <header>
      <app-header/>
    </header>
    <main>
      
      <section>
        <app-jumbotron/>
      </section>
      
      <section>
        <app-section-1/>
      </section>
      
      <section>
        <app-section-2/>
      </section>
      
      <section>
        <app-section-3/>
      </section>
      
      <section>
        <app-section-4/>
      </section>

    </main>

    <footer>
      <app-footer/>
    </footer>

    




   
  </div>
</template>

<script>
import AppFooter from './components/AppFooter.vue'
import AppHeader from './components/AppHeader.vue'
import AppJumbotron from './components/AppJumbotron.vue'
import AppSection1 from './components/AppSection1.vue'
import AppSection2 from './components/AppSection2.vue'
import AppSection3 from './components/AppSection3.vue'
import AppSection4 from './components/AppSection4.vue'


export default {
  name: 'App',
  components: {
    AppHeader,
    AppJumbotron,
    AppSection1,
    AppSection2,
    AppSection3,
    AppSection4,
    AppFooter,
    
  }
}
</script>

<style lang="scss">
@import './styles/general.scss';
</style>
