<template>
    <main class="main-content flex column align-center">
        <div class="intro flex align-center column">
            <img src="../assets/images/illustration-intro.png">
            <h1>All your files in one secure location, accessible anywhere.</h1>
            <p>Fylo stores all your most important files in one secure location. Access them wherever you need, share
                and collaborate with friends family, and co-workers.</p>
            <button class="btn round">get started</button>
        </div>
        <div class="services flex wrap align-center">
            <div class="service">
                <div class="service-img">
                    <img src="../assets/images/icon-access-anywhere.svg" />
                </div>
                <h2>Access your files, anywhere</h2>
                <p>The ability to use a smartphone, tablet, or computer to access your account means your files follow
                    you everywhere.</p>
            </div>
            <div class="service">
                <div class="service-img">
                    <img src="../assets/images/icon-security.svg" />
                </div>
                <h2>Security you can trust</h2>
                <p>2-factor authentication and user-controlled encryption are just a couple of the security features we
                    allow to help secure your file</p>
            </div>
            <div class="service">
                <div class="service-img">
                    <img src="../assets/images/icon-collaboration.svg" />
                </div>
                <h2>Real-time collaboration</h2>
                <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email
                    attachments required.</p>
            </div>
            <div class="service">
                <div class="service-img">
                    <img src="../assets/images/icon-any-file.svg" />
                </div>
                <h2>Store any type of file</h2>
                <p>Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file
                    types to be securely stored and shared.</p>
            </div>
        </div>

        <div class="guide flex align-center">
            <div class="productive-img">
                <img src="../assets/images/illustration-stay-productive.png">
            </div>
            <div class="info flex column">
                <h1>Stay productive, wherever you are</h1>
                <p>Never let location be an issue when accessing your files. Fylo has you covered for all of your file
                    storage needs.</p>
                <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email
                    attachments required.</p>
                <a class="link-to-guide">See how Fylo works <span><img src="../assets/images/icon-arrow.svg"></span></a>
            </div>
        </div>

        <div class="reviews flex">
            <div class="quites">
                <img src="../assets/images/bg-quotes.png">
            </div>
            <div class="review">
                <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team
                    has become a well-oiled collaboration machine.</p>
                <div class="reviewer">
                    <div class="avatar">
                        <img src="../assets/images/profile-1.jpg">
                    </div>
                    <div class="reviewer-info">
                        <h5 class="full-name">Satish Patel</h5>
                        <h6 class="job">Founder & CEO, Huddle</h6>
                    </div>
                </div>
            </div>
            <div class="review">
                <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team
                    has become a well-oiled collaboration machine.</p>
                <div class="reviewer">
                    <div class="avatar">
                        <img src="../assets/images/profile-2.jpg">
                    </div>
                    <div class="reviewer-info">
                        <h5 class="full-name">Bruce McKenzie</h5>
                        <h6 class="job">Founder & CEO, Huddle</h6>
                    </div>
                </div>
            </div>
            <div class="review">
                <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team
                    has become a well-oiled collaboration machine.</p>
                <div class="reviewer">
                    <div class="avatar">
                        <img src="../assets/images/profile-3.jpg">
                    </div>
                    <div class="reviewer-info">
                        <h5 class="full-name">Iva Boyd</h5>
                        <h6 class="job">Founder & CEO, Huddle</h6>
                    </div>
                </div>
            </div>
        </div>
        <div class="contact">
            <h1>Get early access today</h1>
            <p>It only takes a minute to sign up and our free starter tier is extremely generous. If you have any
                questions, our support team would be happy to help you.</p>
            <form action="">
                <input type="email" placeholder="email@example.com">
                <button class="btn round">get started for free</button>
            </form>
        </div>
    </main>
</template>
<script>
export default {
    name: 'main-content',
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