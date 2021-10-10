<template>
<div class="container">
    <NavBar/>
    <Timeline/>
  </div>
</template>

<script>
import Timeline from '../components/Timeline.vue'
import NavBar from '../components/NavBar.vue'

export default {
    components: {
    NavBar,
    Timeline,
  }
}
</script>

<style>

</style>