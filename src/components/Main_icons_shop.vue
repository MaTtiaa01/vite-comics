<script>
export default {
    name: "Main_icons_shop",
    data() {
        return {
            products: [
                {
                    product: "digital comics",
                    img: "buy-comics-digital-comics.png"
                },
                {
                    product: "dc merchandise",
                    img: "buy-comics-merchandise.png"
                },
                {
                    product: "subscriptions",
                    img: "buy-comics-subscriptions.png"
                },
                {
                    product: "comic shop locator",
                    img: "buy-comics-shop-locator.png"
                },
                {
                    product: "dc power visa",
                    img: "buy-dc-power-visa.svg"
                },
            ],
        }
    }

}

</script>
<template>
    <section class="icons_shop">
        <div class="container">
            <div class="row row-cols-5">
                <div class="col d-flex align-items-center" v-for="product, i in products">
                    <div class="product_image">
                        <img :src="`/src/assets/img/${product.img}`" alt="">
                        <!-- <img :src="`../assets/img/${product.img}`" alt=""> -->

                    </div>
                    <div class="product_name">{{ product.product }}</div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../assets/scss/Variables.scss" as *;


.icons_shop {
    background-color: $primary;
    padding: 2rem 0;

    img {
        color: $lighter;
        width: 40px;
        margin-right: 0.5rem;
    }
}
</style>