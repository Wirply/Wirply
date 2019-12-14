<template>
    <section class="section">
        <div class="container has-text-centered">
            <h1>Simple and Transparent Pricing.</h1>
            <h2>Always know what you'll pay.</h2>
        </div>
        <section class="section">
            <div class="container">
                <div class="columns is-3">
                    <div class="column has-text-centered">
                        <!-- Title -->
                        <p class="pricing-title">Single</p>
                        <!-- Price -->
                        <p class="pricing-price">499 EUR <span class="pricing-price-subscript">/ month</span></p>
                        <!-- Features -->
                        <div class="pricing-features">
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="close" size="is-medium" style="color: red; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                        </div>
                        <!-- Button -->
                        <div class="pricing-button">
                            <b-button type="is-primary" size="is-large" expanded>Purchase</b-button>
                        </div>
                    </div>
                    <div class="column has-text-centered">
                        <!-- Title -->
                        <p class="pricing-title">Premium</p>
                        <!-- Price -->
                        <p class="pricing-price">599 EUR <span class="pricing-price-subscript">/ month</span></p>
                        <!-- Features -->
                        <div class="pricing-features">
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                        </div>
                        <!-- Button -->
                        <div class="pricing-button">
                            <b-button type="is-primary" size="is-large" expanded>Purchase</b-button>
                        </div>
                    </div>
                    <div class="column has-text-centered">
                        <!-- Title -->
                        <p class="pricing-title">Enterprise</p>
                        <!-- Price -->
                        <p class="pricing-price">699 EUR <span class="pricing-price-subscript">/ month</span></p>
                        <!-- Features -->
                        <div class="pricing-features">
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>  
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                            <!-- Feature -->
                            <div class="pricing-feature is-flex is-aligned-center is-justified-center">
                                <b-icon icon="check" size="is-medium" style="color: green; margin-right: 10px"></b-icon>
                                <p style="margin-top: 8px">Lorem Ipsum Dollar Sit Amet.</p>
                            </div>
                        </div>
                        <!-- Button -->
                        <div class="pricing-button">
                            <b-button type="is-primary" size="is-large" expanded>Purchase</b-button>
                        </div>
                    </div>
                </div>
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
.column {
    box-shadow: 0 18px 40px rgba(51,51,51,.1);
    margin-left: 1.5rem;
    margin-right: 1.5rem;
    padding-top: 4rem;
    padding-bottom: 4rem;
    padding-left: 2rem;
    padding-right: 2rem;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    border: 1px solid transparent;
    transition: border 0.2s;
}
.column:hover {
    border: 1px solid #86C232;
    box-shadow: 0 10px 20px rgba(134, 194, 50, 0.2);
}
.column:first-child {
    margin-top: 60px;
    margin-bottom: 50px;
}
.column:first-child .pricing-title {
    font-family: 'Gordita Medium';
    font-size: 26px;
}
.column:last-child .pricing-title {
    font-family: 'Gordita Medium';
    font-size: 26px;
}
.column:last-child {
    margin-top: 60px;
    margin-bottom: 50px;
}
.pricing-title {
    font-family: 'Gordita Bold';
    font-size: 32px;
    margin-bottom: 30px;
}
.pricing-price {
    font-family: 'Gordita Bold';
    font-size: 36px;
    margin-bottom: 30px;
}
.pricing-price-subscript {
    font-family: 'Gordita Bold';
    font-size: 18px;
    opacity: 0.8;
}
.pricing-features {
    margin-bottom: 60px;
}
.pricing-feature {
    font-family: 'Gordita Medium';
    font-size: 18px;
    margin-top: 15px;
}
.pricing-button {
    font-family: 'Gordita Medium';
    box-shadow: 0px 18px 42px rgba(51,51,51,.1);
}
</style>

<script>
export default {
    
}
</script>