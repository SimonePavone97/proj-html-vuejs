<template>

    <div>
        <h2 class="mb-4">
            Menu Categories
        </h2>

        <div class="row g-4">
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/appetizers-menu-background.jpg" alt="">
                <span class="centere"> appetizers </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/burgers-menu-background.jpg" alt="">
                <span class="centere"> burgers </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/pizza-menu-background.jpg" alt="">
                <span class="centere"> pizzas </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/fries-menu-background.jpg" alt="">
                <span class="centere"> fries </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/sides-menu-background.jpg" alt="">
                <span class="centere"> sides </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/desserts-menu-background.jpg" alt="">
                <span class="centere"> desserts </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/beverages-menu-background.jpg" alt="">
                <span class="centere"> beverages </span>
            </div>
            <div class="col-3 menue">
                <div class="overlay"></div>
                <img class="img-fluid" src="../../assets/images/specials-menu-background.jpg" alt="">
                <span class="centere"> specials </span>
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
    .menue {
        position: relative;
    }

    .centere {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 1.7em;
        color: #ffff;
    }

    .overlay {

        position: absolute;
        top: 0;
        left: 11px;
        right: 12px;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.4);
    }
</style>