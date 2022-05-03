<template>

    <div class="menu">
        <div class="center text-uppercase">
            <ul class="nav d-flex align-items-center justify-content-between">
                <li class="nav-item" v-for="(element, index) in menuOrder" :key="index">
                    <a class="nav-link" :href="element.url"> {{element.name}} </a>
                    
                </li>
            </ul>

        </div>
    </div>


</template>



<script>
    export default {
        name: 'OrderComp',
        data() {
            return {
                menuOrder: [{
                        name: '24/7 delivery',
                        url: '#',
    
                    },
                    {
                        name: 'over 100 dishes',
                        url: '#',
                        
                    },
                    {
                        name: 'in app ordering',
                        url: '#'
                    },
                    {
                        name: 'fast delivery',
                        url: '#'
                    },
                ]
            }
        }
    }
</script>



<style scoped lang="scss">
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