<template>
  <div>
    <b-navbar variant="faded" type="light">
      <b-navbar-brand href="#">
        <img
          src="../assets/logo_jobizz_violet.png"
          alt="Kitten"
          class="image"
        />
      </b-navbar-brand>
      <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="navbar ml-auto" >
        <b-nav-item class="navbar"><NuxtLink to="/">Home</NuxtLink></b-nav-item>
        <b-nav-item><NuxtLink to="/features">Features</NuxtLink></b-nav-item>
        <b-nav-item href="#">About us</b-nav-item>
         <b-nav-item href="http://51.103.25.25:3000/">
             <button class="button btn">
                 Commencer
             </button> 
         </b-nav-item>
      </b-navbar-nav>
      </b-collapse>
      <!-- <-- <b-nav-text  href="#" class="text-nav">Candidat</b-nav-text>
      <b-nav-text href="#" class="text-nav">Recruteur</b-nav-text> -->
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.image {
  width: 100px;
}
.text-nav{
    align-content: space-between;
}
.button {
        border-radius: 100rem;
        border-color: rgb(129, 141, 229);
        background-color: white;
        color:  rgb(129, 141, 229);
        width: 7rem;
        height: 3rem;
        text-align: start;
        transition: 0.5s;
        }
.button:hover {
        background-color: rgb(129, 141, 229);
        color: white;
        width: 9rem;
        height: 3rem;
    }
    .navbar {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: 600;
        color:  black;
    }
    .navbar:hover{
        color:  rgb(129, 141, 229);
    }

    @media (max-width: 500px) {
        .navbar {
            height: 40vh;
        }
    }
</style>
