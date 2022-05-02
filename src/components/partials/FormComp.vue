<template>

    <div class="container marg d-flex flex-column text-start">
        <div class="row space text-white">
            <div class="col">
                <h6>order online</h6>
                <ul>
                    <li class="pt-3">
                        <a href="#">Appetizers</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Burger</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Pizza</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Fries</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Sides</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Dessert</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Beverages</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Specials</a>
                    </li>
                </ul>
            </div>
            <div class="col">
                <h6>navigate</h6>
                <ul>
                    <li class="pt-3">
                        <a href="#">
                            <font color="#fcd66c">Home</font>
                        </a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Alternate Home</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Menu</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">About</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">News</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Contact Us</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Cart</a>
                    </li>

                </ul>
            </div>
            <div class="col">
                <h6>information</h6>
                <ul>
                    <li class="pt-3">
                        <a href="#">My Account</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Terms Of Service</a>
                    </li>
                    <li class="pt-3">
                        <a href="#">Privacy Policy</a>
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
                <h6>opening hours</h6>
                <ul>
                    <li class="pt-1">
                        Mon - <font color="#fcd66c">10AM to 11PM</font>
                    </li>
                    <li class="pt-1">
                        Tue - <font color="#fcd66c">10AM to 11PM</font>
                    </li>
                    <li class="pt-1">
                        Wed - <font color="#fcd66c">10AM to 11PM</font>
                    </li>
                    <li class="pt-1">
                        Thur - <font color="#fcd66c">10AM to 11PM</font>
                    </li>
                    <li class="pt-1">
                        Fri - <font color="#fcd66c">10AM to 11PM</font>
                    </li>
                    <li class="pt-1">
                        Sat - <font color="#fcd66c">10AM to 1PM</font>
                    </li>
                    <li class="pt-1">
                        Sun - <font color="#fcd66c">10AM to 11PM</font>
                    </li>
                </ul>
            </div>
            <div class="col text-center">
                <h6>voucher</h6>
                <ul>
                    <li>
                        <a href="#">
                            <img class="img-fluid" src="../../assets/images/footer-coupon-200x200.png" alt="">
                        </a> <br>
                    </li>

                    <li class="pt-3">
                        <span>just use the code</span> <br>
                        <span>
                            <font color="#fcd66c" class="text-uppercase fs-4">firstorder</font>
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