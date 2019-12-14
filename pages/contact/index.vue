<template>
    <section class="section">
        <div class="container has-text-centered">
            <h1>Let's make it even more simple.</h1>
            <h2>Leave us a line with your idea.</h2>
        </div>
        <section class="section">
            <div class="container" style="max-width: 800px">
                <b-field label="Your Name">
                    <b-input placeholder="Name..."></b-input>
                </b-field>
                <b-field label="Your Email">
                    <b-input placeholder="Email..."></b-input>
                </b-field>
                <b-field label="Your Message">
                    <b-input type="textarea" placeholder="Message..."></b-input>
                </b-field>
                <b-button type="is-primary">Send Message</b-button>
            </div>
        </section>
    </section>
</template>

<style scoped>
h1 {
    font-family: 'Gordita Medium';
    font-size: 32px;
}
h2 {
    font-family: 'Gordita Medium';
    font-size: 26px;
    opacity: 0.9;
}
.button {
    margin-top: 10px;
}
</style>

<script>
export default {
    
}
</script>