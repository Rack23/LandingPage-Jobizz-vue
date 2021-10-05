<template>
  <div class="container">
        <NavBar/>
        <HeroFeatures/>
  </div>
</template>

<script>
import HeroFeatures from '../components/HeroFeatures.vue'
import LargeCardDisplay from '../components/LargeCardDisplay.vue'
import NavBar from '../components/NavBar.vue'
export default {
    components: { HeroFeatures, NavBar, LargeCardDisplay },}

</script>

<style>

</style>