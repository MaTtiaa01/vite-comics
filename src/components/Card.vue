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
    <div class="col" v-for="comic in comics">
        <div class="card">
            <div class="card_top">
                <img :src="image" alt="">
            </div>
            <div class="card_bottom">{{ title }}</div>
        </div>
    </div>
</template>
