<template>
    <div class="sfondo-footer">
        <FormComp />
        <div class="container mt-5 text-center">
            <LogoComp />
            <SubComp/>
            <EmailComp/>
            <SocialComp/>
        </div>

    </div>
</template>


<script>
    import FormComp from './partials/FormComp.vue'
    import LogoComp from './partials/LogoComp.vue'
    import SubComp from './partials/SubComp.vue'
    import EmailComp from './partials/EmailComp.vue'
    import SocialComp from './partials/SocialComp.vue'
    
    
    export default {
        name: 'FooterComp',
        components: {
            FormComp,
            LogoComp,
            SubComp,
            EmailComp,
            SocialComp,
      
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