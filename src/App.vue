
<script>
import Header from "./components/Header.vue";
import Main_jumbotron from "./components/Main_jumbotron.vue";
import Main_black_bar from "./components/Main_black_bar.vue";
import Main_icons_shop from "./components/Main_icons_shop.vue";
import Footer_top from "./components/Footer_top.vue";
import Footer_bottom from "./components/Footer_bottom.vue";

export default {
  name: "App",
  components: {
    Header,
    Main_jumbotron,
    Main_black_bar,
    Main_icons_shop,
    Footer_top,
    Footer_bottom,
  },
}
</script>

<template>


  <Header></Header>
  <!-- /#site_header -->
  <main id="site_main">
    <Main_jumbotron></Main_jumbotron>
    <!-- /black_bar -->
    <Main_icons_shop></Main_icons_shop>

    <!-- /icons_shop -->

  </main>
  <!-- /#site_main -->
  <footer>

    <Footer_top></Footer_top>
    <Footer_bottom></Footer_bottom>
  </footer>
  <!-- /#site_footer -->

</template>


<style lang="scss" >

</style>