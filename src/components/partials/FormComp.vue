<template>

    <div class="container marg text-start">
        <div class="row space text-white">
            <div class="col text-white">
                <ul>
                    <li class="pb-2" v-for="(element, index) in menuForm1" :key="index">
                        <h6>{{element.title}}</h6>
                        <a :href="element.url"> {{element.list}} </a>
                    </li>
                </ul>
            </div>


            <div class="col">
                <ul>
                    <li class="pb-2" v-for="(element, index) in menuNavigate" :key="index">
                        <h6>{{element.title_2}}</h6>
                        <a :href="element.url"> {{element.list}} </a>

                    </li>

                </ul>
            </div>
            <div class="col">

                <ul>
                    <li class="pb-2" v-for="(element, index) in menuInformation" :key="index">
                        <h6>{{element.title_3}}</h6>
                        <a :href="element.url"> {{element.list}} </a>

                    </li>
                    <li class="pt-3">
                        <a href="#">
                            <img class="img-fluid border border-light border-2 rounded"
                                src="../../assets/images/app-store-badge-200x67.png" alt="">
                        </a>
                    </li>
                    <li class="pt-3">
                        <a href="#">
                            <img class="img-fluid border border-light border-2 rounded"
                                src="../../assets/images/play-store-badge-200x67.png" alt="">
                        </a>
                    </li>
                </ul>
            </div>
            <div class="col">

                <ul>
                    <li class="pb-2" v-for="(element, index) in menuHours" :key="index">
                        <h6>{{element.title_4}}</h6>
                        <span> {{element.date}} <font color="#fcd66c">{{element.hours}}</font></span>
                    </li>

                </ul>
            </div>
            <div class="col text-center">
                <ul>
                    <li v-for="(element, index) in menuVoucher" :key="index">
                        <h6>{{element.title_5}}</h6>
                        <img class="img-fluid" src="../../assets/images/footer-coupon-200x200.png" alt=""> <br>
                        <span>just use the code</span> <br>
                        <span>
                            <font color="#fcd66c" class="text-uppercase fs-4">{{element.sconto}}</font>
                        </span> <br>
                        <span>at checkout</span>
                    </li>

                   


                  
                </ul>
            </div>
        </div>
    </div>

</template>



<script>
    export default {
        name: 'FormComp',
        data() {
            return {
                menuForm1: [{
                        title: 'order online',

                    },
                    {
                        list: 'appetizers',
                        url: '#',

                    },
                    {
                        list: 'burger',
                        url: '#',

                    },
                    {
                        list: 'pizza',
                        url: '#',
                    },
                    {
                        list: 'fries',
                        url: '#',
                    },
                    {
                        list: 'sides',
                        url: '#',
                    },
                    {
                        list: 'desserts',
                        url: '#',
                    },
                    {
                        list: 'beverages',
                        url: '#',
                    },
                    {
                        list: 'specials',
                        url: '#',
                    },
                ],
                menuNavigate: [{
                        title_2: 'Navigate',

                    },
                    {
                        list: 'Home',
                        url: '#',

                    },
                    {
                        list: 'alternate home',
                        url: '#',
                    },
                    {
                        list: 'menu',
                        url: '#',
                    },
                    {
                        list: 'about',
                        url: '#',
                    },
                    {
                        list: 'news',
                        url: '#',
                    },
                    {
                        list: 'contact us',
                        url: '#',
                    },
                    {
                        list: 'cart',
                        url: '#',
                    },
                ],
                menuInformation: [{
                        title_3: 'Information',

                    },
                    {
                        list: 'my account',
                        url: '#',

                    },
                    {
                        list: 'term of service',
                        url: '#',
                    },
                    {
                        list: 'privacy policy',
                        url: '#',
                    },
                ],
                menuHours: [{
                        title_4: 'opening hours',

                    },
                    {
                        date: 'mon -',
                        hours: '10AM to 11PM',
                        url: '#',

                    },
                    {
                        date: 'tue -',
                        hours: '10AM to 11PM',
                        url: '#',
                    },
                    {
                        date: 'wed -',
                        hours: '10AM to 11PM',
                        url: '#',
                    },
                    {
                        date: 'thur -',
                        hours: '10AM to 11PM',
                        url: '#',
                    },
                    {
                        date: 'fri -',
                        hours: '10AM to 11PM',
                        url: '#',
                    },
                    {
                        date: 'sat -',
                        hours: '10AM to 1PM',
                        url: '#',
                    },
                    {
                        date: 'sun -',
                        hours: '10AM to 11PM',
                        url: '#',
                    },
                ],
                menuVoucher: [{
                        title_5: 'Voucher',
                        sconto: 'FIRSTORDER',
                    },

                ]
            }
        }
    }
</script>



<style scoped lang="scss">
    .marg {
        margin-top: 180px
    }

    .space {
        padding-top: 130px;
    }

    h6 {
        text-transform: uppercase;
    }

    ul {
        list-style-type: none;
        padding-left: 0;
        margin-left: 0;

        li {


            a {
                text-decoration: none;
                color: white;
                font-size: 0.8em;
            }

            img {
                width: 160px;

            }
        }
    }
</style>