<template>
  <div id="app">
    <Header />
    <Jumbo />
    <Services />
    <Playlist />
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/js/all.js';
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import Services from './components/Services.vue'
import Playlist from './components/Playlist.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Services,
    Playlist,
    
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@400;500&display=swap');
  @import "../src/styles/style.scss";
#app {
  background-color: #060606;
  font-family: 'Barlow Semi Condensed', Helvetica, Arial, sans-serif;
  
}
</style>
