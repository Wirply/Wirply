<template>
    <section class="section">
        <div class="container">
            <div class="columns">
                <div class="column is-flex is-justified-left">
                    <div class="supfooter-item">
                        Wirply
                    </div>
                </div>
            </div>
            <div class="columns">
                <div class="column is-flex is-justified-left">
                    <div class="footer-item">
                        <a href="/about">
                            ABOUT
                        </a>
                    </div>
                    <div class="footer-item">
                        <a href="/careers">
                            CAREERS
                        </a>
                    </div>
                    <div class="footer-item">
                        <a href="/knowledge">
                            KNOWLEDGE
                        </a>
                    </div>
                </div>
                <div class="column is-flex is-justified-right">
                    <div class="footer-item">
                        <a href="https://facebook.com/wirply">
                            <b-icon icon="facebook-box">Facebook</b-icon>
                        </a>
                    </div>
                    <div class="footer-item">
                        <b-icon icon="linkedin"></b-icon>
                    </div>
                    <div class="footer-item">
                        <b-icon icon="instagram"></b-icon>
                    </div>
                </div>
            </div>
            <div class="columns">
                <div class="column is-flex is-justified-left">
                    <div class="subfooter-item">
                        <a href="/">
                            © 2019 Wirply Inc.
                        </a>
                    </div>
                    <div class="subfooter-item">
                        <a href="/refund-policy">
                            Refund Policy
                        </a>
                    </div>
                    <div class="subfooter-item">
                        <a href="/privacy-policy">
                            Privacy Policy
                        </a>
                    </div>
                    <div class="subfooter-item">
                        <a href="/terms-of-service">
                            Terms of Service
                        </a>
                    </div>
                </div>
                <div class="column is-flex is-justified-right">
                    <div class="subfooter-item">
                        hello@wirply.com
                    </div>
                    <div class="subfooter-item">
                        support@wirply.com
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.section {
    background-color: #311d3f;
    color: #ffffff;
}
.supfooter-item {
    font-family: 'Gordita Bold';
    font-size: 26px;
    padding-inline: 15px;
    color: #e23e57;
}
.footer-item {
    padding-inline: 15px;
    font-family: 'Gordita Medium';
    font-size: 13px;
}
.subfooter-item {
    padding-inline: 15px;
    font-family: 'Gordita Light';
    font-size: 11px;
}
.columns:first-child {
    padding: 0px;
}
.columns:first-child .column {
    padding-bottom: 0px;
}
.columns:last-child {
    padding: 0px;
}
.columns:last-child .column {
    padding: 0px;
    padding-left: 10px;
    padding-right: 10px;
}
</style>

<script>
export default {
    
}
</script>