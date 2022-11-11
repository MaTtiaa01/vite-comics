<script>
export default {
    name: "Footer_bottom"
}
</script>

<template>
    <div class="footer_bottom">
        <div class="container d-flex justify-content-between">

            <div class="call_to_action">
                <button class="text-uppercase">sing-up now!</button>
            </div>
            <div class="follow_us d-flex align-items-center">
                <a class="text-uppercase" href="#">follow us</a>
                <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>
@use "../assets/scss/Variables.scss" as *;

.footer_bottom {
    background-color: $dark;
    padding: 2rem 0;

    .follow_us {
        a {
            margin-left: 1rem;
        }

        a.text-uppercase {
            text-decoration: none;
            font-weight: bold;
        }
    }
}



button {
    background-color: $dark;
    font-size: 15px;
    font-weight: 500;
    color: $lighter;
    border: 2px solid $primary;
    padding: 0.5rem 1.5rem;
}
</style>