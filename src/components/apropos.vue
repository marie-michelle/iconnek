<template>
  <div class="">
    <h1>{{ msg }}</h1>
<!-- TRIGGER MODAL À PROPOS -->

        <button type="button" class="btn btn-secondary mt-4" data-toggle="modal" data-target="#apropos">
            <span class="white">À PROPOS</span>
          </button>
   
    <div class="col-xs-12 col-sm-12 col-md-6 offset-lg-1 col-lg-4 offset-xl-1 col-xl-4 ">
    <img :src="require('../assets/img/corpo-img-3.jpg')" alt="Image corpo 3" name='Image corpo 3' class="image-style ">
    </div>



<!-- MODAL À PROPOS -->
  <div class="modal fade" id="apropos" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          ...
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline-secondary" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-secondary">Save changes</button>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {

  name: 'apropos',
  props: {
  }
}
</script>

<style scoped>

</style>