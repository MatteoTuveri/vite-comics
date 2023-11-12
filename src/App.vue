<template>
  <header>
      <HeaderComponent />
  </header>
  <main>
      <MainComponent />
  </main>
  <footer>
      <FooterComponent />
  </footer>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  }

}
</script>

<style lang="scss" scoped>
</style>