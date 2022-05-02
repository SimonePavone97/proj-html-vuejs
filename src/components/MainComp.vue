<template>

    <div>
        <div class="text-center ">
            <FoodComp />
        </div>
        <div>
            <SalesComp />
        </div>
        <div class="container">
            <MenuComp/>
            <AllergiesComp/>
        </div>
        <div>
            <DownComp/>
        </div>
        <div>
            <NewsComp/>
        </div>


    </div>

</template>


<script>
    import FoodComp from '../components/partials/FoodComp.vue'
    import SalesComp from '../components/partials/SalesComp.vue'
    import MenuComp from '../components/partials/MenuComp.vue'
    import AllergiesComp from '../components/partials/AllergiesComp.vue'
    import DownComp from '../components/partials/DownComp.vue'
    import NewsComp from '../components/partials/NewsComp.vue'

    export default {
        name: 'MainComp',
        components: {
            FoodComp,
            SalesComp,
            MenuComp,
            AllergiesComp,
            DownComp,
            NewsComp
        }
    }
</script>


<style scoped lang="scss">



</style>