<template>
  <div class="whoContainer">
     <WhoText></WhoText>
     <WhoPicture></WhoPicture>
  </div>
</template>

<script>
import WhoText from './Who/WhoText.vue'
import WhoPicture from './Who/WhoPicture.vue'

export default {
  name: 'Who', 
  components: {
    WhoText,
    WhoPicture
  }
}
</script>

<style scoped>
.whoContainer {
    width: 100%;
    height: 140vh;
}
</style>
