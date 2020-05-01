<template>
  <div class="examplesContainer">
      <div class="titleCard">
          <h2>DIE MOBILIAR -- DIRECTOR'S CUT</h2>
          <h3>die Mobiliar</h3>
      </div>
      <div id="card1" class="videoCard"></div>
      <div id="card2" class="videoCard"></div>
      <div id="card3" class="videoCard"></div>
  </div>
</template>

<script>
export default {
  name: 'Examples', 
}
</script>

<style scoped>
.examplesContainer {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    height: 100vh;
}
.titleCard {
    display: flex;
    justify-content: center;
    text-align: center;
    flex-direction: column;
    height: 50%;
    width: 50%;
    background-image: url("../assets/portrait.jpg");
    background-size: cover;
    filter: grayscale(80%);
}
.videoCard {
    height: 50%;
    width: 50%;
}
#card1 {
    background-color: rgb(53, 54, 56);
}
#card2 {
    background-color: rgb(56, 60, 65);
}
#card3 {
    background-color: rgb(25, 30, 36);
}
</style>
