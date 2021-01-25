<template>
  <div class="">
            <!-- NAVBAR -->
        <div class="">
            <div class="collapse" id="navbarToggleExternalContent">
<!--                <nav>-->
<!--                  <router-link to="/">Accueil</router-link>-->
<!--                  <router-link to="/connexion">Connexion</router-link>-->
<!--                  <router-link to="/a-propos">À propos</router-link>-->
<!--                  <router-link to="/contact">Contact</router-link>-->
<!--                  <router-link to="/compte">Compte</router-link>-->
<!--                  <router-link to="/validation">Validation</router-link>-->
<!--                </nav>-->
<!--              <router-view></router-view> -->
<!--            </div>-->
            <nav class="navbar navbar-dark nav-color">
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <svg src="../assets/img/iconnek-logo-colo-1000x.svg" alt="logo iconnek"></svg>
              <form class="form-inline my-2 my-lg-0">
                <button type="button" class="btn btn-outline-secondary" data-toggle="modal" data-target="#connexion">
                    Connexion
                  </button>
              </form>
            </nav>
          </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'navigation',
  props: {
  }
}
</script>

<style scoped>

img {
    height: 2em;
}
.nav-color{
    background-color: rgb(10, 10, 10);
}


</style>
