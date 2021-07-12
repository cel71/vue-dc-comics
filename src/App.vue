<template>
  <div id="app">
    <Header />
    <Main />
    <Iconbar />
    <Linkbar />
    <Footer />
  </div>
</template>

<script>
  import Header from "./components/Header.vue"
  import Main from "./components/Main.vue"
  import Iconbar from "./components/Iconbar.vue"
  import Linkbar from "./components/Linkbar.vue"
  import Footer from "./components/Footer.vue"

export default {
  name: "App",
  components: {
    Header,
    Main,
    Iconbar,
    Linkbar,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./style/app.scss";

</style>
