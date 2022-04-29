<template>
    <div class="container">
        <h1 class="margin"> our most popular dishes</h1>
        <div class="row">
            <div class="col">
                <img class="img-fluid" src="../../assets/images/skin-on-fries-400x571.jpg" alt="">
                <h3 class="my-3">skin on fries</h3>
                <span class="fw-light"> $3.00-$6.00 </span>
            </div>
            <div class="col">
                <img class="img-fluid" src="../../assets/images/choco-cookie-frappe-400x571.jpg" alt="">
                <h3 class="my-3">skin on fries</h3>
                <span class="fw-light"> $4.99 </span>
            </div>
            <div class="col">
                <img class="img-fluid" src="../../assets/images/donut-burger-400x571.jpg" alt="">
                <h3 class="my-3">skin on fries</h3>
                <span class="fw-light"> $6.99 </span>
            </div>

        </div>

        <button type="button" class="btn btn-danger text-uppercase fw-bold my-5">start your order</button>
    </div>

</template>



<script>
    export default {
        name: 'FoodComp',
    }
</script>



<style scoped lang="scss">

    .margin {
        margin-top: 80px;
        margin-bottom: 80px;
    }

    h1 {
        color: black
    }

    span {
        color: red;
    }
</style>