<template>
  <div class="contactContainer">
      <h3>CINESIGHT KLG</h3>
      <h3>CinesightStrasse 15</h3>
      <h3>3008 Bern</h3>
  </div>
</template>

<script>
export default {
  name: 'Contact', 
}

</script>

<style scoped>
.contactContainer {
    width: 100%;
    height: 50vh;
    background-image: url("../assets/contact.jpg");
    background-size: cover;
    display: flex;
    text-align: center;
    justify-content: center;
    flex-direction: column;
}
</style>
