<template>

    <nav class="navbar navbar-expand-lg">
        <ul class="navbar-nav">
            <!--<li class="nav-item">
                <a class="nav-link" href="#">
                    <font color="#fcd66c">Home</font>
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Order Online</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">News</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contact Us</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Carrello</a>
            </li>-->
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