<template>
  <div id="app">
    <Header />
    <Jumbo />
    <Services />
    <Playlist />
    <Mailing />
    <Card />
    <Blog />
    <Cta />
    <Sponsor />
    <Video />
    <Footer />
    <Copyright />
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/js/all.js';
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import Services from './components/Services.vue'
import Playlist from './components/Playlist.vue'
import Mailing from './components/Mailing.vue'
import Card from './components/Card.vue'
import Blog from './components/Blog.vue'
import Cta from './components/Cta.vue'
import Sponsor from './components/Sponsor.vue'
import Video from './components/Video.vue'
import Footer from './components/Footer.vue'
import Copyright from './components/Copyright.vue'


export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Services,
    Playlist,
    Mailing,
    Card,
    Blog,
    Cta,
    Sponsor,
    Video,
    Footer,
    Copyright,
    
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@400;500&display=swap');
@import "../src/styles/partials/_variables.scss";
@import "../src/styles/style.scss";
  
#app {
  background-color: $bgdarkColor;
  font-family: 'Barlow Semi Condensed', Helvetica, Arial, sans-serif;
  
}
</style>
