<script>
export default {
    name: "Main_jumbotron"
}
</script>

<template>
    <div class="jumbotron">

    </div>
</template>

<style lang="scss" scoped>
.jumbotron {
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
    height: 400px;

    .container {
        position: relative;
    }

    button {
        position: absolute;
        left: 1rem;
        bottom: -1rem;
    }
}
</style>