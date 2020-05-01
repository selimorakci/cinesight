<template>
  <div class="whatContainer">
      <div class="topSection">
            <div class="container">
                <div class="words">
                    <p class="title">Planung</p>
                    <p class="title">Realisierung</p>
                    <p class="title">Bearbeitung</p>
                </div>
                <p>CINESIGHT bietet eine einfache und unkomplizierte Kommunikation, eine zielführende Beratung und Konzepte nach Mass.<br><br>
                    CINESIGHT macht Kamera, Riging, Ton, Licht, Maske, Schnitt, Compositing, Motion Design, Farbkorrektur und Vertonung.<br><br>
                    CINESIGHT plant und organisiert gründlich, Location scouting, Casting und Setgestalltung gehören auf Wunsch dazu.</p>
            </div>
      </div>
      <div class="bottomSection">
            <p class="bottomText">CINESIGHT bietet eine einfache und unkomplizierte Kommunikation, eine zielführende Beratung und Konzepte nach Mass.</p>
            <p class="bottomText">CINESIGHT macht Kamera, Riging, Ton, Licht, Maske, Schnitt, Compositing, Motion Design, Farbkorrektur und Vertonung.</p>
            <p class="bottomText">CINESIGHT plant und organisiert gründlich, Location scouting, Casting und Setgestalltung gehören auf Wunsch dazu.</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'What', 
}
</script>

<style scoped>
.whatContainer {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 100vh;
}
.topSection {
    text-align: center;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 80%;
}
.container {
    width: 100%;
}
.bottomSection {
    background-color: #333333;
    height: 20%;
    width: 100%;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    border-bottom: 2px solid rgb(197, 197, 197);
}
.words {
    display: flex;
    justify-content: space-evenly;
    margin-bottom: 100px;
}
.title {
    font-size: 40px;
}
.bottomText {
    color: white;
    width: 25%;
    font-weight: lighter;
}
</style>
