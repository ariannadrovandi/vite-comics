<template>
    <div class="bg-dark">
        <div class="container d-flex justify-content-between align-items-center py-2">
            <button class="btn border border-primary rounded-0 text-white text-uppercase">Sign-Up Now!</button>
            <ul class="d-flex align-items-center list-unstyled">
                <li class="text-primary text-uppercase pe-3">Follow Us</li>
                <li class="pe-3"><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                <li class="pe-3"><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                <li class="pe-3"><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                <li class="pe-3"><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                <li class="pe-3"><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterBottomComponent'
    }
</script>

<style lang="scss" scoped>
    ul {
        margin: 0;
    }
</style>