<template>
  <div class="Hero container">
      <div class="text-container">
      <h1>The first marketplace <br> of small job and extra.</h1>
      <p class="snippet">
          Jobizz is the first marketplace to help people to find a small job or an extra.
          Scroll down to learn more about us or access to our application
      </p>
      <button class="button btn">Télécharger l'application</button>
      </div>
      <img src="../assets/test_iphone.png" alt="" class="image">
      
  </div>
</template> 

<script>
export default {

}
</script>

<style scoped>
    .Hero {
        height: 50vh;
        position: relative;
        display: flex;
        padding: 5rem 0;
        align-items: flex-start;
        justify-content: space-between;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .text-container {
        width: 50%;
        margin-top: 4rem;
    }
    .header {
        font-weight: 900;
        font-size: 5rem;
    }
    .snippet {
        color: grey;
        font-size: 1rem;
        margin-top: 2rem;
        margin-bottom: 2rem;
    }
    .image {
        width: 40rem;
        margin-top: 2rem;
    }
    .overlay {
        background: rgba(0, 0, 0, 0);
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
    }
    .button {
        padding: 1rem 4rem;
        border-radius: 100rem;
        background-color: rgb(129, 141, 229);
        color: white;
        width: 20rem;
        font-weight: 700;
        transition: 0.5s;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .button:hover {
        width: 21.5rem;
        border-color: rgb(129, 141, 229);
        background-color: white;
        color:  rgb(129, 141, 229);
    }
    @media (max-width: 500px) {
        .Hero {
            height: 40vh;
        }
    }
</style>