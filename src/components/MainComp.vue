<template>

    <div>
        <div class="text-capitalize text-center ">
            <FoodComp/>
        </div>
        <div>
            <SalesComp/>
        </div>

    </div>

</template>


<script>
import FoodComp from '../components/partials/FoodComp.vue'
import SalesComp from '../components/partials/SalesComp.vue'
    export default {
        name: 'MainComp',
        components: {
            FoodComp,
            SalesComp
        }
    }
</script>


<style scoped lang="scss">


</style>