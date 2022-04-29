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
        </div>

    </div>

</template>


<script>
    import FoodComp from '../components/partials/FoodComp.vue'
    import SalesComp from '../components/partials/SalesComp.vue'
    import MenuComp from '../components/partials/MenuComp.vue'

    export default {
        name: 'MainComp',
        components: {
            FoodComp,
            SalesComp,
            MenuComp
        }
    }
</script>


<style scoped lang="scss">



</style>