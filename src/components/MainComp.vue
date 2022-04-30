<template>

    <div>
        <div class="text-capitalize text-center ">
            <FoodComp />
        </div>
        <div>
            <SalesComp />
        </div>
        <div class="container text-capitalize">
            <MenuComp/>
            <AllergiesComp/>
        </div>
        <div>
            <DownComp/>
        </div>


    </div>

</template>


<script>
    import FoodComp from '../components/partials/FoodComp.vue'
    import SalesComp from '../components/partials/SalesComp.vue'
    import MenuComp from '../components/partials/MenuComp.vue'
    import AllergiesComp from '../components/partials/AllergiesComp.vue'
    import DownComp from '../components/partials/DownComp.vue'

    export default {
        name: 'MainComp',
        components: {
            FoodComp,
            SalesComp,
            MenuComp,
            AllergiesComp,
            DownComp
        }
    }
</script>


<style scoped lang="scss">



</style>