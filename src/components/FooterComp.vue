<template>
    <div class="sfondo-footer">
        <FormComp />
    </div>
</template>


<script>

import FormComp from './partials/FormComp.vue'
    export default {
        name: 'FooterComp',
        components:{
            FormComp
        }
    }
</script>


<style lang="scss">
    .sfondo-footer {
        background-image: url('../assets/images/footer-background-scaled.jpg');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
    }
</style>