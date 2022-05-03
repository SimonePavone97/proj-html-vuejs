<template>

    <nav class="navbar navbar-expand-lg">
        <ul class="navbar-nav">

            <li class="nav-item" v-for="(element, index) in menuLink" :key="index">
                <a class="nav-link" :href="element.url"> {{element.link}} </a>
            </li>
        </ul>
    </nav>




</template>



<script>
    export default {
        name: 'ListComp',
        data() {
            return {
                menuLink: [{
                        link: 'home',
                        url: '#'
                    },
                    {
                        link: 'order online',
                        url: '#'
                    },
                    {
                        link: 'about',
                        url: '#'
                    },
                    {
                        link: 'news',
                        url: '#'
                    },
                    {
                        link: 'contact us',
                        url: '#'
                    },
                    {
                        link: 'carrello',
                        url: '#'
                    },
                ]
            }
        }
    }
</script>



<style scoped lang="scss">
    a {
        color: #ffff !important;
    }
</style>