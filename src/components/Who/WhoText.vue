<template>
  <div class="whoTextContainer">
      <div class="logoContainer">
        <img class="logo" src="../../assets/logo.png">
      </div>
      <div class="textContainer">
        <p class="text">Emotionen die bleiben.<br><br>Cinesight ist ein junges und dynamisches Startup Unternehmen, welches 2020 in Bern gegründet wurde. Die Geschäftsleitung übernehmen zwei Mediamatiker, welche die Faszination vom Filmen nun zum Beruf machen. Cinematische Bilder in höchster Qualität übermitteln Emotionen die bleiben. Dies steht im Zentrum des Unternehmens. Cinesight produziert professionelle und nachhaltige Videos. Das Unternehmen ist überzeugt von qualitativ hochwertiger Bildsprache. Ziel ist es durch einen massgeschneiderten Content die gewünschte Zielgruppe zu erreichen. Mit kreativen Ideen und der passenden Story berührt Cinesight Menschen. Professionelles Equipment führt zu einer aussergewöhnlichen Erfahrung. Wir bieten ein allumfassendes Filmerlebnis welches nachhaltig im Gedächtnis bleibt.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WhoText', 
}
</script>

<style scoped>
.whoTextContainer {
    width: 100%;
    height: 40vh;
    display: flex;
}
.logo {
    height: 200px;
}
.logoContainer {
    width: 40%;
    display: flex;
    align-items: center;
    justify-content: center;
}
.textContainer {
    width: 60%;
    display: flex;
    align-items: center;
}
.text {
    width:85%
}
</style>
