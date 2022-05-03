<template>
    <div class="container">
        <h1 class="margin"> our most popular dishes</h1>
        <div class="row">
            <div class="col">

                <img src="../../assets/images/skin-on-fries-400x571.jpg" alt="">
                <div v-for="(element, index) in topFoods" :key="index">
                    <h3 class="my-3"> {{element.title}}</h3>
                    <span class="fw-light"> {{element.price}} </span>
                </div>


            </div>
            <div class="col">

                <img src="../../assets/images/choco-cookie-frappe-400x571.jpg" alt="">
                <div v-for="(element, index) in topFoods" :key="index">
                    <h3 class="my-3"> {{element.title_2}}</h3>
                    <span class="fw-light"> {{element.price_2}} </span>
                </div>

            </div>
            <div class="col">

                <img src="../../assets/images/donut-burger-400x571.jpg" alt="">
                <div v-for="(element, index) in topFoods" :key="index">
                    <h3 class="my-3"> {{element.title_3}}</h3>
                    <span class="fw-light"> {{element.price_3}} </span>
                </div>

            </div>

        </div>

        <button type="button" class="btn btn-danger text-uppercase fw-bold my-5">start your order<i
                class="fa-solid fa-arrow-right ms-3"></i></button>
    </div>

</template>



<script>
    export default {
        name: 'FoodComp',
        data() {
            return {
                topFoods: [{
                        title: 'skin on fries',
                        price: '$3.00-$6.00',
                    },
                    {
                        title_2: 'choco cookie frappe',
                        price_2: '$4.99',
                    },
                    {
                        title_3: 'the donut burger',
                        price_3: '$6.99',
                    },

                ]
            }
        }
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