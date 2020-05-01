<template>
  <div id="app">
    <div class="navbarContainer">
      <a class="navElement">CINESIGHT</a>
      <a v-on:click = "goToAnchor('who')" class="navElement">Wer</a>
      <a v-on:click = "goToAnchor('what')" class="navElement">Was</a>
      <a v-on:click = "goToAnchor('examples')" class="navElement">Our Work</a>
      <a v-on:click = "goToAnchor('clients')" class="navElement">Clients</a>
      <a v-on:click = "goToAnchor('contact')" class="navElement">Contact</a>
    </div>
    <Header/>
    <Who id="who"/>
    <What id="what"/>
    <Examples id="examples"/>
    <Clients id="clients"/>
    <Contact id="contact"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Who from './components/Who.vue'
import What from './components/What.vue'
import Examples from './components/Examples.vue'
import Clients from './components/Clients.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Header,
    Who,
    What,
    Examples,
    Clients,
    Contact
  },
  methods: {
      goToAnchor(anchor) {
        var element = document.getElementById(anchor);
        element.scrollIntoView({behavior: "smooth", block: "start", inline: "nearest"});
      }
  }
}
</script>

<style>
#headerContainer {
  width: 100%;
  height: 100vh;
}
html {
  padding: 0;
  margin: 0;
}
body {
  margin: 0;
}
#app {
  margin: 0;
  padding: 0;
}
.navbarContainer {
    position: absolute;
    display: flex;
    width: 100%;
    height: 60px;
}
.navElement {
    width: 20%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
}
p, h1, h2, h3, a {
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
h2,h3{
    color: white;
}
a {
  cursor: pointer;
}
</style>
