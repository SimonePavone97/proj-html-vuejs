<template>

    <div>
        <h2 class="mb-4">
            Menu Categories
        </h2>

        <div class="row g-4">
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/appetizers-menu-background.jpg" alt="">
                <span class="center"> appetizers </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/burgers-menu-background.jpg" alt="">
                <span class="center"> burgers </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/pizza-menu-background.jpg" alt="">
                <span class="center"> pizzas </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/fries-menu-background.jpg" alt="">
                <span class="center"> fries </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/appetizers-menu-background.jpg" alt="">
                <span class="center"> sides </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/burgers-menu-background.jpg" alt="">
                <span class="center"> desserts </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/pizza-menu-background.jpg" alt="">
                <span class="center"> beverages </span>
            </div>
            <div class="col-3 menu">
                <img class="img-fluid" src="../../assets/images/fries-menu-background.jpg" alt="">
                <span class="center"> specials </span>
            </div>
        </div>

    </div>

</template>



<script>
    export default {
        name: 'MenuComp',
    }
</script>



<style scoped lang="scss">

.menu {
  position: relative;
}

.center {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 1.7em;
  color: #ffff;
}




</style>