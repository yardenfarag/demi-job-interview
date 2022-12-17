<template>
    <footer class="flex main-layout full align-center column">
        <div class="logo">
            <img src="../assets/images/logo.svg">
        </div>
        <div class="footer-content main-layout flex">
            <div class="location flex">
                <img src="../assets/images/icon-location.svg">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
                    et dolore magna aliqua</p>
            </div>
            <div class="contact-info">
                <ul class="clean-list flex column">
                    <li class="flex">
                        <img src="../assets/images/icon-phone.svg">
                        <p>+1-543-123-4567</p>
                    </li>
                    <li class="flex">
                        <img src="../assets/images/icon-email.svg">
                        <p>example@fylo.com</p>
                    </li>
                </ul>
            </div>
            <div class="about-us">
                <ul class="clean-list flex column">
                    <li>
                        <a>about us</a>
                    </li>
                    <li>
                        <a>jobs</a>
                    </li>
                    <li>
                        <a>press</a>
                    </li>
                    <li>
                        <a>blog</a>
                    </li>
                </ul>
            </div>
            <div class="contact-us">
                <ul class="clean-list flex column">
                    <li>
                        <a>contact us</a>
                    </li>
                    <li>
                        <a>terms</a>
                    </li>
                    <li>
                        <a>privacy</a>
                    </li>
                </ul>
            </div>
            <div class="social-media">
                <!-- <svg class="svg" xlink="../assets/images/facebook.svg"></svg> -->
                <img class="facebook" src="../assets/images/facebook.svg" />
                <img class="twitter" src="../assets/images/twitter.svg" />
                <img class="instagram" src="../assets/images/instagram.svg" />
            </div>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'app-footer',
    components: {},
    data() {
        return {};
    },
    created() { },
    methods: {},
    computed: {},
    unmounted() { },
};
</script>
<style>

</style>