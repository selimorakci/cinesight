<template>
  <div class="clientsContainer">
      <div class="container">
        <h1>Clients</h1>
        <div class="logoContainer">
                <img class="logo" src="../assets/logo.png">
                <img class="logo" src="../assets/logo.png">
                <img class="logo" src="../assets/logo.png">
                <img class="logo" src="../assets/logo.png">
                <img class="logo" src="../assets/logo.png">
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Clients', 
}
</script>

<style scoped>
.clientsContainer {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 50vh;
    align-items: center;
    justify-content: center;
}
.logoContainer {
    margin-top: 20px;
    display: flex;
    justify-content: space-evenly;
}
.logo {
    height: 200px;
}
.container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    height: fit-content;
    text-align: center;
}
h1 {
    margin-top: 0;
}
</style>
