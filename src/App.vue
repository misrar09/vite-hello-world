<!-- JavaScript Section -->
<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {  // Ad d file names as objects
  components: {
    AppTitle,
    AppHero,
  }
}
</script> 


<!-- HTML Section -->
<template>
  <AppHero /> <!-- This is the tag for the file AppHero -->
  <AppTitle /><!-- This is the tag for the file AppTitle -->
</template>


<!-- CSS Section -->
<style scoped></style>
