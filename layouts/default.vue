<template>
  <div>
    <!-- Global Plugins -->
    <!-- Animate On Scroll -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
    <!-- Cookie Consent -->
    <!-- <b-notification style="margin-bottom: 0px">
      We use cookies on our websites to offer the best browsing experience. Continuing to browse means that You accept and agree to this.
    </b-notification> -->
    <!-- TopBar -->
    <TopBar />
    <!-- MenuBar -->
    <MenuBar />
    <nuxt>
    </nuxt>
    <!-- Footer -->
    <Footer />
  </div>
</template>

<style>
.notification {
  border-top-left-radius: 0px;
  border-top-right-radius: 0px;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
  background-color: #252525;
  color: #ffffff;
}
.button {
  border-radius: 10px;
}
.section {
  padding: 100px;
}
.is-justified-right {
  justify-content: flex-end;
}
.is-justified-left {
  justify-content: flex-start;
}
.is-justified-center {
  justify-content: center;
}
.is-aligned-center {
  align-items: center;
}
.is-aligned-left {
  align-items: flex-start;
}
.is-aligned-right {
  align-items: flex-end;
}
.is-flex-column {
  display: flex;
  flex-direction: column;
}
@font-face {
  font-family: 'Gordita Regular';
  src: url('~assets/fonts/GorditaRegular.otf');
}
@font-face {
  font-family: 'Gordita Bold';
  src: url('~assets/fonts/GorditaBold.otf');
}
@font-face {
  font-family: 'Gordita Light';
  src: url('~assets/fonts/GorditaLight.otf');
}
@font-face {
  font-family: 'Gordita Medium';
  src: url('~assets/fonts/GorditaMedium.otf');
}
a {
  text-decoration: none;
  color: #ffffff;
}
a:hover {
  color: #e23e57;
}
</style>

<script>
import TopBar from '~/components/TopBar.vue'
import MenuBar from '~/components/MenuBar.vue'
import Footer from '~/components/Footer'

export default {
  components: {
    TopBar,
    MenuBar,
    Footer
  },
}
</script>