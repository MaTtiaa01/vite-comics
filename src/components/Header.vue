<script>
export default {
    name: "Header",
    data() {
        return {
            pages: [
                {
                    page: "charachters"
                },
                {
                    page: "comics"
                },
                {
                    page: "movies"
                },
                {
                    page: "tv"
                },
                {
                    page: "games"
                },
                {
                    page: "collectibles"
                },
                {
                    page: "videos"
                },
                {
                    page: "fans"
                },
                {
                    page: "news"
                },
                {
                    page: "shop"
                }
            ],
            active: null,
        }
    }
}
</script>

<template>
    <header id="site_header">
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" class="" alt="">
            </div>
            <div class="navbar">
                <ul>
                    <li v-for="page, i in pages">
                        <a :class="i === 1 ? 'active' : ''" href="#">{{ page.page }}</a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped >
@use "../assets/scss/Variables.scss" as *;

header {
    background-color: $lighter;

    .container {
        display: flex;
        justify-content: space-between;
        padding: 1rem 0;
        align-items: center;
    }

    ul {
        list-style: none;
        display: flex;

        a {
            margin-left: 1rem;
            color: $dark;
            text-decoration: none;
            font-size: 15px;
            font-weight: bold;
            text-transform: uppercase;

            &.active {
                color: $primary;
            }
        }
    }
}
</style>