<template>
  <div id="app">
    <Header />
    <Main :comics="comics" />
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
  import ComicsJson from "./jsons/dc-comics.json"

export default {
  name: "App",
  components: {
    Header,
    Main,
    Iconbar,
    Linkbar,
    Footer,
  },
  data: function () {
    return {
      comics: ComicsJson,
    }
  }
};
</script>

<style lang="scss">
@import "./style/app.scss";

</style>
