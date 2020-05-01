<template>
  <div class="navbarContainer">
      <a class="navElement">CINESIGHT</a>
      <a class="navElement">Was</a>
      <a class="navElement">Wer</a>
      <a class="navElement">Clients</a>
      <a v-on:click = "goToAnchor(contact)" class="navElement">Contact</a>
  </div>
</template>

<script>
export default {
  name: 'Navbar', 
  
}
</script>

<style scoped>
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
</style>
