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
                    product: "digital comics",
                    img: "buy-comics-merchandise.png"
                },
                {
                    product: "digital comics",
                    img: "buy-comics-shop-locator.png"
                },
                {
                    product: "digital comics",
                    img: "buy-comics-subscription.png"
                },
                {
                    product: "digital comics",
                    img: ""
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
                <div class="col" v-for="product, i in products">
                    <div class="product_image">
                        <img :src="`../assets/img/${product.img}`" alt="">
                    </div>
                    <div class="product_name">{{ product.product }}</div>
                </div>
            </div>
        </div>
    </section>
</template>

<style>

</style>