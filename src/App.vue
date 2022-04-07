<template>
  <div id="app">
  <Header />
    
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/js/all.js';
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header,
    
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@400;500&display=swap');
  @import "../src/styles/style.scss";
#app {
  font-family: 'Barlow Semi Condensed', Helvetica, Arial, sans-serif;
}
</style>
