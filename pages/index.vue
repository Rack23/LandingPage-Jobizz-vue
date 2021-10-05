<template>
<div class="container">
  <NavBar/>
  <Hero/>
  
</div>
</template>

<script>
import Hero from '../components/Hero.vue'
import LargeCardDisplay from '../components/LargeCardDisplay.vue'
import NavBar from '../components/NavBar.vue'
import Footers from '../components/Footers.vue'

export default {
  components: { Hero, NavBar, LargeCardDisplay, Footers },}
</script>
