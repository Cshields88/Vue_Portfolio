<template>
  <div class="container-fluid">
   <app-header></app-header>
   <app-portfolio></app-portfolio>
   <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import About from "./components/About.vue";
import Portfolio from "./components/Portfolio.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    appHeader: Header,
    appAbout: About,
    appPortfolio: Portfolio,
    appContact: Contact,
    appFooter: Footer
  }
};
</script>

<style lang="scss">
:root {
  // Colors
  --mint: #4cf7c6;
  --blue-grey: #4e576d;
  // Fonts
  --headings: "Nunito", sans-serif;
  --body: "Roboto", sans-serif;
}
body {
  background-color: black;
  color: white;
}
</style>
