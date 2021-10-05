<template>
  <div class="container">
      <h4>Partie suivante</h4>
      <p class="snippet">User say these are the best fire extinguihshers to rent if you house is burning.</p>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.container {
    margin-top: 5rem;
    margin-left: 40rem;
}
    .header {
        font-weight: 700;
        font-size: 1.5rem;:
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .snippet {
        color: grey;
        margin-bottom: 1.5rem;
    }
    .cards-container {
        display: flex;
        justify-content: space-between;
    }
    
    @media (max-width: 500px) {
        .Hero {
            height: 40vh;
        }
    }
</style>