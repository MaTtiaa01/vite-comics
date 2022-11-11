<script>
export default {
    name: "Card",
    props: {
        image: String,
        title: String,
    }
}
</script>

<template>
    <div class="col">
        <div class="box ">
            <div class="box_top">
                <img :src="image" alt="">
            </div>
            <div class="box_bottom text-uppercase">{{ title }}</div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/Variables.scss" as *;


.box_bottom {
    color: $lighter;
    margin-top: 1rem;
    font-weight: bold;
}
</style>
