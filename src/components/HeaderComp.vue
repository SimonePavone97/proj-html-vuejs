<template>
    <div class="container">
        <div class="d-flex align-items-start justify-content-between pt-5">
            <LogoComp />
            <ListComp />
        </div>
        <div>
            <TitleHead />
        </div>
        <div>
            <OrderComp />
        </div>

    </div>
</template>


<script>
    import LogoComp from './partials/LogoComp.vue'
    import ListComp from './partials/ListComp.vue'
    import TitleHead from './partials/TitleHead.vue'
    import OrderComp from './partials/OrderComp.vue'

    export default {
        name: 'HeaderComp',
        components: {
            LogoComp,
            ListComp,
            TitleHead,
            OrderComp
        }
    }
</script>


<style lang="scss">
    
</style>