<template>
  <div class="bg-dark">
<header class="home-hero header " role="banner">
  <video autoplay="" id="heroVideo" loop="" muted="" poster="" class="filter">
    <source src="../assets/video/circuit-27725.mp4" type="video/mp4" />
  </video>
<!--  <img alt="poster image mobile" class="poster img-fluid mx-auto d-block d-sm-none" src="https://raw.githubusercontent.com/solodev/hero-with-video-bg/master/images/hero-video-poster.jpg" />-->
  <div class="container d-flex flex-row">
    <div class="row">
      <div class="col-lg-12 d-flex flex-column justify-content-center text-white py-md-5 text-container pl-5 ml-5">
        <h2 class="display-4 mb-0 green">{{ titre1 }}<span class="d-block font-weight-bold">{{ company }}</span></h2>
        <p class="lead my-4">{{ tagline1 }}
          <br>{{ tagline2 }}</p>
        <a class="btn btn-outline-light w-max mt-2" href="/a-propos" tabindex="0">À propos</a>
      </div>
    </div>
  </div>

</header>

<!-- CONTENU -->

<div class="row pt-5 full greed m-0 center" no-gutters>
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-4 offset-lg-1 col-xl-4 offset-xl-1">
        <h1 class="white display-4">L'entreprise</h1>
        <br>
    </div>
</div>
<hr class="style">
<div class="row full" no-gutters>
    <div class="col-xs-12 col-sm-12 col-md-6 col-lg-4 offset-lg-1 col-xl-4 offset-xl-1 pt-5 mt-5">
        <h1>Lorem, ipsum dolor.</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Accusamus consequuntur corrupti culpa. Veniam minima voluptates nobis optio? Autem, alias necessitatibus.</p>
        <ul>
            <li>Lorem 1</li>
            <li>Lorem 2</li>
            <li>Lorem 3</li>
            <li>Lorem 4</li>
        </ul>
        <hr>
<a-propos></a-propos>
  </div>
  </div>
  </div>
</template>

<script>
// import aPropos from './a-propos.vue'
export default {
  data() {
    return{
    name: 'accueil',
    titre1: 'Gagnez du temps!',
    company: 'iconnek',
    tagline1: 'Synchronisez vos inventaires.',
    tagline2: 'Facilitez-vous la vie!'
    }
  
  },
 
  props: {
  }
}
</script>

<style scoped>


 * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Lato", sans-serif;
  font-weight: 400;
  font-size: 1.2rem;
  line-height: 1.7;
  padding: 30px;
  width: 100%;
}

.header {
  height: 95vh;
  background-size: cover;
  background-position: top;
  clip-path: polygon(0 0, 100% 0, 100% 75vh, 0 100%);
  box-shadow: inset 0 20px 20px -20px rgba(0, 0, 0, 0.5);

}

.logo-box {
  position: absolute;
  top: 40px;
  left: 40px;
}

.logo {
  height: 35px;
}

@media (max-width: 575.98px) {
  header.home-hero video {
    display: none;
  }
}

header.home-hero {
  position: relative;
  height: 89vh;
  min-height: 25rem;
  width: 100%;
  overflow: hidden;
}

header.home-hero .container {
  position: relative;
  height: 100%;
}

.bg-dark {
  background-image:
    linear-gradient(#141414, #0f0f0f, #000);
}

.btn {
  max-width: 250px;
  border-radius: 0;
  font-weight: 500;
}

header.home-hero video {
  position: absolute;
  top: 50%;
  left: 50%;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: 0;
  -ms-transform: translateX(-50%) translateY(-50%);
  -moz-transform: translateX(-50%) translateY(-50%);
  -webkit-transform: translateX(-50%) translateY(-50%);
  transform: translateX(-50%) translateY(-50%); 
}

.filter{
  filter: grayscale(80%); 
  z-index: 2;
    height: 37.8em;
    background-color: #4b5257;
    opacity: 0.05;
}

@media (max-width: 575.98px) {
  header.home-hero video {
    display: none;
  }
}

header.home-hero img.poster {
  height: 100vh;
  min-height: 100vh;
  object-fit: cover;
  object-position: bottom right;
  position: absolute;
  top: 0;
  left: 0;
}
.btn-outline-light{
  color: #ec8753;
  border-color: #ec8753;
  

}
.btn-outline-light:hover{
  background-color: #00846e;
  border-color: #00846e;
  color: #0f0f0f;

}



.center{
  align-items: center;
  justify-content: center;
}


</style>
