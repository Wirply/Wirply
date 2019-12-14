<template>
    <section class="hero is-medium">
        <script src="https://cdn.jsdelivr.net/npm/typeit@6.1.1/dist/typeit.min.js"></script>
        <div class="hero-body">
            <div class="container">
                <div class="columns">
                    <div class="column is-6 is-flex-column is-justified-center" data-aos="fade-right" data-aos-delay="200" data-aos-duration="300">
                        <h1 class="title">Your Gateway into Success.</h1>
                        <h2 class="subtitle">Modern IT solutions for modern businesses. Trust us with Your success.</h2>
                    </div>
                    <div class="column is-6 is-flex-column is-justified-center is-aligned-center" data-aos="fade-left" data-aos-delay="2300" data-aos-duration="500">
                        <img src="illustration_5.jpg">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.hero {
    font-family: 'Gordita Light';
    background-size: cover;
    background-position: center;
}
.title {
    font-family: 'Gordita Bold';
    font-size: 52px;
}
.subtitle {
    font-family: 'Gordita Bold';
    font-size: 32px;
    opacity: 0.9;
}
img {
    height: 500px;
    width: 500px;
}
</style>

<script>
export default {
    mounted () {
        new TypeIt('.title', {speed: 75, cursor: false}).go()
    },
}
</script>