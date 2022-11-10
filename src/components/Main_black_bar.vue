<script>
export default {
    name: "Main_back_bar"
}
</script>

<template>

    <section class="black_bar ">
        <div class="container">
            <h2> Content goes here</h2>
        </div>
    </section>

</template>

<style lang="scss" scoped>
@use "../assets/scss/Variables.scss" as *;

section {
    background-color: $dark;
    color: $lighter;
    padding: 2rem 0;
}
</style>