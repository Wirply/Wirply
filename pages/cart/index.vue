<template>
    <section class="section">
        <div class="container">
            <h1>Shopping Cart</h1>
            <!-- Items -->
            <div class="columns">
                <div class="column">
                    <section class="section">
                        <div class="columns items has-text-centered">
                            <div class="column is-flex is-aligned-center is-justified-center">
                                <b-icon icon="server" size="is-large"></b-icon>
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                Premium Bot Service
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                1 VNT.
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                599 EUR
                            </div>
                        </div>
                        <div class="columns items has-text-centered">
                            <div class="column is-flex is-aligned-center is-justified-center">
                                <b-icon icon="server" size="is-large"></b-icon>
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                Premium Bot Service
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                1 VNT.
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                599 EUR
                            </div>
                        </div>
                        <div class="columns items has-text-centered">
                            <div class="column is-flex is-aligned-center is-justified-center">
                                <b-icon icon="server" size="is-large"></b-icon>
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                Premium Bot Service
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                1 VNT.
                            </div>
                            <div class="column is-flex is-aligned-center is-justified-center">
                                599 EUR
                            </div>
                        </div>
                    </section>
                </div>
            </div>

            <!-- Buttons -->
            <div class="columns">
                <div class="column is-flex is-aligned-center is-justified-left">
                    <b-icon icon="arrow-left-thick"></b-icon>
                    <span style="margin-top: 5px; margin-left: 10px"><a href="/">Continue Shopping</a></span>
                </div>
                <div class="column is-flex-column is-aligned-right is-justified-center">
                    <span style="font-size: 32px; font-family:'Gordita Medium'">Total <span style="font-family:'Gordita Bold'">1449 EUR</span></span>
                    <b-button type="is-primary" size="is-medium">Purchase</b-button>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
* {
    font-family: 'Gordita Medium'
}
h1 {
    font-size: 32px;
}
.items {
    padding: 20px;
    border: 1px solid transparent;
    border-radius: 15px;
    box-shadow: 0 0px 10px rgba(51,51,51,.1);
    transition: border 0.2s;
    margin-bottom: 50px;
}
.items:hover {
    border: 1px solid #7957d5;
    box-shadow: 0 0px 10px rgba(121, 87, 213, 0.2);
}
.items:last-child {
    margin-bottom: 0px
}
.section {
    padding-left: 50px;
    padding-right: 50px;
}
</style>

<script>
export default {
    
}
</script>