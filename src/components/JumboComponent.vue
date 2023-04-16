<template>
    <div class="jumbo">
        <img src="../assets/img/jumbotron.jpg" alt="hero">
        <div class="container">
            <button class="text-uppercase fw-bold fs-5 btn btn-primary rounded-0">Current Series</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'JumboComponent',
    }
</script>

<style lang="scss" scoped>
    .jumbo {
        width: 100vw;
        height: 20vh;
        position: relative;
        img {
            display: block;
            width: 100%;
            height: 20vh;
            object-fit: cover;
            object-position: top;
        }
    }
</style>