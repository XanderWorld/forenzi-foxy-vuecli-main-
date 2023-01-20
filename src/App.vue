<template>
  <div id="app">
    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";

import MainComponent from "./components/MainComponent.vue";

import FooterComponent from "./components/FooterComponent.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "~@fortawesome/fontawesome-free/css/all.css";
@import "./assets/style/global.scss";
@import "./assets/style/variables.scss";

@import url("https://fonts.googleapis.com/css2?family=East+Sea+Dokdo&display=swap");
body * {
  font-family: "East Sea Dokdo", cursive;
  font-size: 1rem;
}
</style>
