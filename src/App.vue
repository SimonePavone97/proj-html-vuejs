<template>
  <div>
    <header>
      <div class="jumbo">
        <HeaderComp />
      </div>

    </header>

    <main>
      <MainComp />
    </main>

    <footer>
      <FooterComp/>
    </footer>
  </div>


</template>

<script>
  import "bootstrap"
  import HeaderComp from './components/HeaderComp.vue'
  import MainComp from './components/MainComp.vue'
  import FooterComp from './components/FooterComp.vue'

  export default {
    name: 'App',
    components: {
      HeaderComp,
      MainComp,
      FooterComp
    }
  }
</script>

<style lang="scss">
  @import "bootstrap/dist/css/bootstrap.min.css";
  @import './assets/filescss/global.scss';


  .jumbo {
    background-image: url("./assets/images/home-background-hero-scaled.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    
  }
</style>