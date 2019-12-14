<template>
    <section class="section">
        <div class="container has-text-centered">
            <h1>Like our customers, stats that keep on growing.</h1>
            <h2>We make sure to never miss a count.</h2>
            <div class="section" style="padding-bottom: 0px; border: 0px">
                <div class="columns">
                    <div class="column">
                        <h1>0</h1>
                        <h2>Happy Customers</h2>
                    </div>
                    <div class="column">
                        <h1>0</h1>
                        <h2>Projects Finished</h2>
                    </div>
                    <div class="column">
                        <h1>0</h1>
                        <h2>Coffee Made</h2>
                    </div>
                    <div class="column">
                        <h1>0</h1>
                        <h2>Servers Updated</h2>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.section {
    border-top: 1px solid #ebebeb;
    border-bottom: 1px solid #ebebeb;
}
.section {
    background-color: #fafafa;
}
h1, h2 {
    font-family: 'Gordita Medium'
}
h1 {
    font-size: 32px;
}
h2 {
    font-size: 26px;
    opacity: 0.8;
}
.column h1 {
    font-size: 46px;
    font-family: 'Gordita Bold'
}
</style>

<script>
export default {
    mounted () {
    },
    components: {
    },
}
</script>