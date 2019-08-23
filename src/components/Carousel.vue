<template>
  <div class="carousel">
    <header>
      <section class="row" id="carousel1">
        <div id="carouselheader" class="carousel slide" data-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="assets/heroimage4.jpg" class="d-block w-100 h100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="assets/heroimage2.jpg" class="d-block w-100 h100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="assets/foodImg.jpg" class="d-block w-100 h100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="assets/capstoneImg.PNG" class="d-block w-100 h100" alt="...">
            </div>
          </div>
          <a class="carousel-control-prev" href="#carouselheader" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselheader" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </section>
    </header>
  </div>
</template>

<script>
  export default {
    name: 'carousel',
    components: {

    }
  }
</script>

<style>

</style>