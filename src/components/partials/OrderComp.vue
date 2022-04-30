<template>

    <div class="menu">
        <div class="center d-flex align-items-center justify-content-between text-uppercase">
            <a class="nav-link" href="#"><i class="fa-solid fa-clock mx-3"></i>24/7 delivery</a>
            <a class="nav-link" href="#"><i class="fa-solid fa-burger mx-3"></i>over 100 dishes</a>
            <a class="nav-link" href="#"><i class="fa-solid fa-mobile-screen mx-3"></i>in app ordering</a>
            <a class="nav-link" href="#"><i class="fa-solid fa-car mx-3"></i>fast delivery</a>
        </div>
    </div>


</template>



<script>
    export default {
        name: 'OrderComp',
    }
</script>



<style lang="scss">
    a {
        color: #020201 !important;
    }

    .menu {
        position: relative;
    }


    .center {
        background-color: white;
        padding: 20px 20px;
        width: 100%;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%); 
        
    }
</style>