<script>
import comics from "../assets/data/dc-comics.js";
import Card_comic from "./Card.vue";

export default {
    name: "Main_comics_card",
    components: {
        Card_comic,

    },
    data() {
        return {
            comics: comics,

        }
    },
}
</script>

<template>
    <div class="comics_cards">

        <div class="container text-center py-5 ">
            <button class="series text-uppercase">current series</button>
            <div class="row row-cols-2 row-cols-sm-4 row-cols-md-6 g-4">
                <Card_comic v-for="comic in comics" :image="comic.thumb" :title="comic.series">
                </Card_comic>
            </div>
            <button class="text-uppercase load">load more</button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/Variables.scss" as *;

.container {
    position: relative;
}

.comics_cards {
    background-color: $dark;
}

button.series {
    position: absolute;
    left: 0;
    top: -1rem;
    background-color: $primary;
    color: $lighter;
    font-size: 18px;
    font-weight: bold;
    padding: 0.5rem 1.5rem;
    border: 1px solid $primary;
}

button.load {
    color: $lighter;
    background-color: $primary;
    padding: 0.25rem 1.5rem;
    font-weight: 400;
    font-size: 15px;
    border: 1px solid $primary;
    margin-top: 2rem;
}
</style>