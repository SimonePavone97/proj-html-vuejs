<template>

    <div class="">

        <div class="pt-5">
            <input type="email" class="form-control rounded-pill no-upper text-dark"  placeholder="you@email.com">
        </div>

        <div class="d-grid pt-3">
            <button class="btn btn-danger rounded-pill text-uppercase fw-bold" type="button">subscribe</button>
        </div>


    </div>

</template>


<script>
    export default {
        name: 'EmailComp',

    }
</script>


<style scoped lang="scss">
  
.no-upper {
        text-transform: none !important;
        
    }

</style>