<template>
  <div>
   <app-header></app-header>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import About from "./components/About.vue";
import Portfolio from "./components/Portfolio.vue";
import Contact from "./components/Contact.vue";

export default {
  components: {
    appHeader: Header,
    appAbout: About,
    appPortfolio: Portfolio,
    appContact: Contact
  }
};
</script>

<style lang="scss">
</style>
