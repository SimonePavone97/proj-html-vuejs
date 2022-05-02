<template>

    <div>
        <div class="jumbo text-capitalize">
            <div class="padd container text-white">
                <span class="font-2">download our</span>
                <p class="font">

                    <font color="#fcd66c">ordering app</font>

                </p>

                <div class="d-flex mt-5">
                    <img class="img-fluid" src="../../assets/images/app-store-badge-200x67.png" alt="">
                    <img class="img-fluid ms-3" src="../../assets/images/play-store-badge-200x67.png" alt="">
                </div>
                
            </div>

        </div>

        <div class="container text-end mt-4">
            <button type="button" class="btn btn-danger text-uppercase fw-bold my-5">start your order<i
                    class="fa-solid fa-arrow-right ms-3"></i></button>

        </div>
    </div>


</template>


<script>
    export default {
        name: 'DownComp',

    }
</script>


<style scoped lang="scss">
    .jumbo {
        background-image: url("../../assets/images/app-ordering-scaled.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;

    }

    .padd {
        padding-top: 100px;
        padding-bottom: 100px;
    }

    .font {
        font-size: 4em;
    }

    .font-2 {
        font-size: 3em;
    }
</style>