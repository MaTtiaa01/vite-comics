<script>
export default {
    name: "Footer_top"
}
</script>

<template>
    <section class="footer_top">
        <div class="container">
            <div class="row row-cols-2">
                <div class="col">
                    <div class="row left">
                        <div class="col-2 ">
                            <div class="box d-flex flex-column align-items-end ">

                                <h4 class="text-uppercase ">Dc comics</h4>
                                <ul>
                                    <li><a href="#">Charachters</a></li>
                                    <li><a href="#">Comics</a></li>
                                    <li><a href="#">Movies</a></li>
                                    <li><a href="#">TV</a></li>
                                    <li><a href="#">Games</a></li>
                                    <li><a href="#">Videos</a></li>
                                    <li><a href="#">News</a></li>
                                </ul>
                                <h4 class="text-uppercase align-self-start">Shop</h4>
                                <ul>
                                    <li><a href="#">Shop DC</a></li>
                                    <li><a href="#">Shop DC Collectibles</a></li>
                                </ul>
                            </div>
                        </div>
                        <div class="col-2 ">
                            <div class="box d-flex flex-column align-items-end ">

                                <h4 class="text-uppercase align-self-start">dc</h4>
                                <ul>
                                    <li><a href="#">Terms of us</a></li>
                                    <li><a href="#">Privacy policy(New)</a></li>
                                    <li><a href="#">Ad choices</a></li>
                                    <li><a href="#">Advertising</a></li>
                                    <li><a href="#">Jobs</a></li>
                                    <li><a href="#">Subscriptions</a></li>
                                    <li><a href="#">Talent Workshops</a></li>
                                    <li><a href="#">CPSC Certificates</a></li>
                                    <li><a href="#">Ratings</a></li>
                                    <li><a href="#">Shop Help</a></li>
                                    <li><a href="#">Contact US</a></li>
                                </ul>
                            </div>
                        </div>
                        <div class="col-2 ">
                            <div class="box d-flex flex-column align-items-end ">

                                <h4 class="text-uppercase align-self-start">sites </h4>
                                <ul>
                                    <li><a href="#">DC</a></li>
                                    <li><a href="#">MAD magazine</a></li>
                                    <li><a href="#">DC Kids</a></li>
                                    <li><a href="#">DC Universe</a></li>
                                    <li><a href="#">DC Power Visa</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class=" dc_background">
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
@use "../assets/scss/Variables.scss" as *;

.footer_top {
    background-image: url(../assets/img/footer-bg.jpg);
}



h4 {
    color: $lighter;
    margin: 1rem 0;
    font-size: 20px;
}

ul {
    list-style: none;
    margin-bottom: 1rem;


    a {
        text-decoration: none;
        color: $light-dark;
    }
}

.dc_background {
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: center;
}
</style>