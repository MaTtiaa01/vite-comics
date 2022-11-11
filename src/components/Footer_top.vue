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
                    <div class="row left gx-4">
                        <div class="col-2 ">
                            <h4 class="text-uppercase">Dc comics</h4>
                            <ul>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                            </ul>
                        </div>
                        <div class="col-2 ">
                            <h4 class="text-uppercase">dc</h4>
                            <ul>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                            </ul>
                        </div>
                        <div class="col-2 ">
                            <h4 class="text-uppercase">sites </h4>
                            <ul>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">Movies</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col dc_background">

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