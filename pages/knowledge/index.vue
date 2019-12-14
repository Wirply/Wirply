<template>
    <div>
        <!-- Hero -->
        <div class="hero is-medium">
            <!-- Hero Body -->
            <div class="hero-body">
                <!-- Container -->
                <div class="container has-text-centered">
                    <!-- Title -->
                    <h1>How can we help You?</h1>
                    <!-- Input -->
                    <b-field size="is-large">
                        <b-input icon="magnify" expanded></b-input>
                        <p class="control">
                            <button class="button is-primary">Search</button>
                        </p>
                    </b-field>
                </div>
            </div>
        </div>
        <!-- Categories -->
        <section class="section">
            <div class="container has-text-centered">
                <h1>We have some awesome articles prepared.</h1>
                <h2>Take a look around.</h2>
            </div>
            <!-- Article Categories -->
            <section class="section is-flex is-justified-center is-aligned-center" style="padding-bottom: 70px">
                <div class="container has-text-centered">
                    <div class="columns is-flex is-justified-center">
                        <div class="column is-flex-column is-aligned-center">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Payments
                        </div>
                        <div class="column is-flex-column is-aligned-center">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Account
                        </div>
                        <div class="column is-flex-column is-aligned-center">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Security
                        </div>
                        <div class="column is-flex-column is-aligned-center ">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Management
                        </div>
                    </div>
                    <div class="columns is-flex is-justified-center">
                        <div class="column is-flex-column is-aligned-center">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Payments
                        </div>
                        <div class="column is-flex-column is-aligned-center">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Account
                        </div>
                        <div class="column is-flex-column is-aligned-center">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Security
                        </div>
                        <div class="column is-flex-column is-aligned-center ">
                            <b-icon icon="credit-card-multiple" size="is-large" style="margin-bottom: 15px"></b-icon>
                            Management
                        </div>
                    </div>
                </div>
            </section>
        </section>
    </div>
</template>

<style scoped>
* {
    font-family: 'Gordita Medium'
}
.hero {
    background-color: #311d3f;
    color: #ffffff;
}
.container {
    max-width: 800px
}
.container h1 {
    margin-bottom: 15px
}
.section .container h1 {
    margin-bottom: 0;
    color: #252525;
}
.section .container h2 {
    color: #252525;
}
.columns:first-child {
    margin-bottom: 70px;
}
.column {
    box-shadow: 0 10px 20px rgba(51,51,51,.1);
    margin-left: 30px;
    margin-right: 30px;
    padding-top: 50px;
    padding-bottom: 50px;
    padding-right: 80px;
    padding-left: 80px;
    border-radius: 15px;
    min-width: 280px;
    font-size: 22px;
    font-family: 'Gordita Bold';
    border: 1px solid transparent;
    transition: border 0.2s;
}
.column:hover {
    border: 1px solid #7957d5;
    box-shadow: 0 10px 20px rgba(121, 87, 213, 0.2);
}
h1 {
    font-size: 32px;
}
h2 {
    font-size: 26px;
    opacity: 0.8;
}
</style>

<script>
export default {
    
}
</script>