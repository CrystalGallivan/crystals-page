<template>
  <div class="home">
    <footer class="container">
      <section class="row" id="laicons">
        <div class="col-8" id="frontend">
          <i class="fab fa-html5 fa-5x"></i>
          <i class="fab fa-bootstrap fa-5x"></i>
          <i class="fab fa-js-square fa-5x"></i>
          <i class="fab fa-vuejs fa-5x"></i>
          <!-- <i class="fab fa-angular fa-5x"></i> -->
        </div>
        <div class="col-4" id="backend">
          <i class="fab fa-node fa-5x"></i>
          <i class="fab fa-node-js fa-5x"></i>
          <!-- <i class="fab fa-python fa-5x"></i> -->
        </div>
      </section>
      <section class="row" id="blank3"></section>
      <hr id="line" />
      <section class="row">
        <div class="col-2" id="blankspace"></div>
        <div class="col-4" id="socialmedia">
          <a href="https://www.facebook.com/crystal.gallivan"><i class="fab fa-facebook-square fa-4"></i></a>
          <!-- <i class="fab fa-instagram fa-4"></i> -->
          <a href="https://github.com/CrystalGallivan" target="_blank" rel="noopener noreferrer"><i
              class="fab fa-github fa-4"></i></a>
          <!-- <i class="fab fa-twitter fa-4"></i> -->
          <a href="https://www.linkedin.com/in/crystal-gallivan/"><i class="fab fa-linkedin fa-4-in"></i></a>
          <h1>Contact Me@</h1>
        </div>
        <div class="col-6" id="blankspace"></div>
      </section>
    </footer>
  </div>

</template>

<script>
  export default {
    name: 'home',
    components: {

    }
  }
</script>

<style>
  #line {
    margin-top: 0.1rem;
    margin-bottom: 0.1rem;
    border: 0;
    border-top: 1px solid rgba(0, 0, 0, .1);
  }

  #socialmedia {
    background-color: black;
    color: white;
    height: 75px;
    font-size: 20pt;
    display: flex;
    align-items: center;
    justify-content: space-around;

  }

  #blankspace {
    background-color: black;
    color: white;
    height: 75px;
    font-size: 20pt;
    display: flex;
    align-items: center;
    justify-content: center;
    justify-content: space-around;

  }

  #blank3 {
    background-color: black;
    height: 15px;
    outline-color: white;
  }

  #line {
    margin-top: 0.1rem;
    margin-bottom: 0.1rem;
    border: 0;
    border-top: 1px solid rgba(0, 0, 0, .1);
  }

  #socialmedia {
    background-color: black;
    color: white;
    height: 75px;
    font-size: 20pt;
    display: flex;
    align-items: center;
    justify-content: space-around;

  }

  #blankspace {
    background-color: black;
    color: white;
    height: 75px;
    font-size: 20pt;
    display: flex;
    align-items: center;
    justify-content: center;
    justify-content: space-around;

  }
</style>