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
    }
}
</script>

<template>
    <div class="container">
        <div class="row row-cols-2 row-cols-sm-4 row-cols-md-6">
            <Card_comic v-for="comic in comics" :image="comic.thumb" :title="comic.series"></Card_comic>
        </div>
    </div>
</template>

<style lang="scss" scoped>

</style>