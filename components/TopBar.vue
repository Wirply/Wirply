<template>
    <section class="topbar">
        <div class="container">
            <div class="columns is-vcentered">
                <div class="column is-6">
                    <div class="topbar-item">
                        Wirply | Your Gateway into Success.    
                    </div>
                </div>
                <div class="column is-6">
                    <div class="topbar-items is-flex is-justified-right">
                        <div class="topbar-item has-text-weight-semibold">
                            hello@wirply.com
                        </div>
                        <div class="topbar-item has-text-weight-semibold">
                            support@wirply.com
                        </div>
                        <div class="topbar-item">
                            Sign In
                        </div>
                        <div class="topbar-item">
                            <b-dropdown hoverable aria-role="list">
                                <a slot="trigger">
                                    Language
                                </a>

                                <b-dropdown-item aria-role="listitem">Lithuanian</b-dropdown-item>
                                <b-dropdown-item aria-role="listitem">English</b-dropdown-item>
                                <b-dropdown-item aria-role="listitem">Russian</b-dropdown-item>
                            </b-dropdown>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.topbar {
    background-color: #311d3f;
    color: #ffffff;
    padding: 15px;
}
.topbar-item {
    padding-inline: 10px;
    font-size: 13px;
    font-family: 'Gordita Medium'
}
</style>

<script>
export default {
    
}
</script>