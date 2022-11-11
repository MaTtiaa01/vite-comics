<script>
import comics from "../assets/data/dc-comics.js";
export default {
    name: "Main_comics_card",
    data() {
        return {
            comics: comics,
        }
    }
}
</script>

<template>
    {{ comics }}
    <div class="container">
        <div class="row row-cols-2 row-cols-sm-4 row-cols-md-6">
            <div class="col" v-for="comic in comics"> {{ comic.length }} </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    height: 200px;
}
</style>