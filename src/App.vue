<template>
  <div>
    <header>
      <HeaderComp/>
    </header>
    
    <main>
      <MainComp/>
    </main>   
  </div>
    

</template>

<script>
import "bootstrap"
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp
  }
}
</script>

<style lang="scss">
@import "bootstrap/dist/css/bootstrap.min.css";
@import './assets/filescss/global.scss';

header {
        background-image: url("./assets/images/home-background-hero-scaled.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        height: 100vh;
        color: white;
    }


</style>
