<template>
    <section class="section">
        <!-- Flickity -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/flickity/2.2.1/flickity.css" integrity="sha256-i0KDsIhbwcVgJz9I+HmresG9y1LHTjFBahxDTUvN378=" crossorigin="anonymous" />
        <script src="https://cdnjs.cloudflare.com/ajax/libs/flickity/2.2.1/flickity.pkgd.min.js" integrity="sha256-3Maq7M1TC8sOke8B4gRkhfGtETqGWq+xenQO7k2mHjI=" crossorigin="anonymous"></script>
        <div class="container has-text-centered">
            <h1 class="title">Great words from one of our customers.</h1>
            <div class="section" style="padding-bottom: 0px">
                <div class="container main-carousel">
                    <div class="carousel-cell">
                        <img src="avatar.jpg">
                        <h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sagittis metus magna, eget porta mauris mattis eget.</h1>
                        <h2>Matt Wellick</h2>
                        <h3>CEO of Cyprus National Bank</h3>
                    </div>
                    <div class="carousel-cell">
                        <img src="avatar.jpg">
                        <h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sagittis metus magna, eget porta mauris mattis eget.</h1>
                        <h2>Matt Wellick</h2>
                        <h3>CEO of Cyprus National Bank</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
h1 {
    font-family: 'Gordita Medium';
    font-style: italic;
    font-size: 18px;
    opacity: 0.8;
}
h2 {
    margin-top: 20px;
    font-family: 'Gordita Medium';
    font-size: 16px;
}
h3 {
    font-family: 'Gordita Medium';
    font-size: 14px;
}
img {
    border-radius: 50%;
    margin-bottom: 20px;
    height: 150px;
    width: 150px;
}
.main-carousel {
    max-width: 700px;
}
.carousel-cell {
    width: 100%
}
.title {
    font-family: 'Gordita Medium';
    font-style: normal;
    font-weight: 500;
    font-size: 32px;
    color: #000000;
}
</style>

<script>
export default {
    mounted () {
        let main_carousel = document.querySelector('.main-carousel')
        let flickity = new Flickity(main_carousel, {
            autoPlay: true,
            pageDots: false,
            prevNextButtons: false,
        })
    },
}
</script>