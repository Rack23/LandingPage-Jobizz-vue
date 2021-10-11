<template>
<div>
    <NavBar/>
    <img class="vector" width="900" src="~/assets/Frame.png"/>
    <div class="container">
    <Features/>
    </div>
    </div>
</template>

<script>
import Features from '../components/Features.vue'
import NavBar from '../components/NavBar.vue'

export default {
    components: {
        Features,
        NavBar,
    }

}
</script>

<style>
.vector {
  position: absolute;
}
</style>
