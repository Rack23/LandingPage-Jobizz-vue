<template>
<div>
  <div class="container">
    <NavBar/>
  </div>
  <Hero />
</div>
</template>

<script>
import Hero from '../components/Hero.vue'
import NavBar from '../components/NavBar.vue'
import Footers from '../components/Footers.vue'
import Timeline from '../components/Timeline.vue'
import "../node_modules/timeline-vuejs/dist/timeline-vuejs.css";

export default {
  components: { Hero, NavBar, Footers },}
</script>
