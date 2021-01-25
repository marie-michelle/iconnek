<template>
  <div class="">
     <div class="container">
                <div class="row center pt-5">
                    <div class="col-6">
                        <div class="jumbotron shadow bg-blue">
              <h1 class="display-4 white">Contact</h1>
              <p class="lead white">Pour nous écrire, veuillez remplir le formulaire.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    </p>

<form>
    <div class="form-group">
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Courriel">
      </div>
      <div class="input-group mb-3">
        <div class="input-group-prepend">
        
          <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Sujet</button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Information</a>
            <a class="dropdown-item" href="#">Soumission</a>
            <a class="dropdown-item" href="#">Soutient technique</a>
            <a class="dropdown-item" href="#">Autre</a>
          </div>
        </div>
        <input type="text" class="form-control" aria-label="Text input with dropdown button">
      </div>
      <div class="form-group">
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="Votre message..."></textarea>
      </div>

      <button type="submit" class="btn btn-secondary">Soumettre</button>
</form>
             
            
              </div>
            </div>
          </div>
        </div>
    </div>

</template>

<script>
export default {
  name: 'contact',
  props: {
  }
}
</script>

<style scoped>

</style>