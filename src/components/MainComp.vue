<template>

    <div class="container text-capitalize text-center ">
        
        <FoodComp/>

    </div>

</template>


<script>
import FoodComp from '../components/partials/FoodComp.vue'
    export default {
        name: 'MainComp',
        components: {
            FoodComp
        }
    }
</script>


<style scoped lang="scss">


</style>