<template>
    <section class="menubar">
        <div class="container">
            <div class="columns is-vcentered">
                <div class="column is-4">
                    <div class="menubar-item has-text-weight-bold is-size-3">
                        <a href="/" style="font-family: 'Gordita Bold'">
                            Wirply
                        </a>
                    </div>
                </div>
                <div class="column is-4">
                    <div class="menubar-items is-flex is-aligned-center">
                        <div class="menubar-item">
                            <a href="/services">
                                Services
                            </a>
                        </div>
                        <div class="menubar-item">
                            <a href="/products">
                                Products
                            </a>
                        </div>
                        <div class="menubar-item">
                            <a href="/about">
                                About
                            </a>
                        </div>
                        <div class="menubar-item">
                            <a href="/careers">
                                Careers
                            </a>
                        </div>
                        <div class="menubar-item">
                            <a href="/contact">
                                Contact
                            </a>
                        </div>
                    </div>
                </div>
                <div class="column is-4">
                    <div class="menubar-items is-flex is-justified-right is-aligned-center">
                        <a href="/contact" class="menubar-item">
                            <b-button type="is-primary" outlined>Contact Sales</b-button>
                        </a>
                        <b>OR</b>
                        <a href="/cart" class="menubar-item">
                            <b-button type="is-primary">Purchase Now</b-button>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.menubar {
    background-color: #ffffff;
    padding: 20px;
}
.menubar-item {
    font-family: 'Gordita Medium';
    font-size: 16px;
    padding-inline: 10px;
}
.menubar-item:hover {
    color: #7957d5;
    transition: color 0.3s;
}
a {
    color: #000000;
}
</style>

<script>
export default {
    
}
</script>