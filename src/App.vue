<template>
  <div id="app">
    <div class="wrap-app">
      <div class="container">
        <Header />
        <Home />
        <Cards />
      </div>
    </div>
    <Info />
    <Contact />
    <div class="container">
      <Projects />
    </div>
  </div>
</template>

<script>

import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
import Header from "./views/Header.vue";
import Home from "./views/Home.vue";
import Cards from "./views/Cards.vue";
import Info from "./views/Info.vue";
import Contact from "./views/Contact.vue";
import Projects from "./views/Projects.vue";

export default {
  name: "App",
  components: {
    Header,
    Home,
    Cards,
    Info,
    Contact,
    Projects,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
}

.wrap-app {
  background-image: url("https://www.thebalancesmb.com/thmb/iIV7A--elKPnwhB1_-T3gRVfEUM=/1540x1155/smart/filters:no_upscale()/Stocksy_woman-writing-laptop_476082-57ab432d3df78cf459975331.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
</style>
