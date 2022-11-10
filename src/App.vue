
<script>
import Header from "./components/Header.vue";
import Main_black_bar from "./components/Main_black_bar.vue";
import Main_icons_shop from "./components/Main_icons_shop.vue";
import Main_jumbotron from "./components/Main_jumbotron.vue";

export default {
  name: "App",
  components: {
    Header,
    Main_black_bar,
    Main_icons_shop,
    Main_jumbotron,
  },
}
</script>

<template>
  <div id="app" class="container">

    <Header></Header>
    <!-- /#site_header -->
    <main id="site_main">
      <Main_black_bar></Main_black_bar>
      <!-- /black_bar -->
      <Main_icons_shop></Main_icons_shop>

      <!-- /icons_shop -->
      <Main_jumbotron></Main_jumbotron>

      <!-- /jumbotron -->

    </main>
    <!-- /#site_main -->
    <footer id="site_footer">

    </footer>
    <!-- /#site_footer -->
  </div>
</template>


<style>

</style>