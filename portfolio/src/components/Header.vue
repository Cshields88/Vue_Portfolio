<template>
  <b-navbar toggleable="md" type="light" variant="">

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand href="#" class="logo-name">Chris <br> Shields</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">

      
    <b-navbar-nav>
      <b-nav-item href="#">Home</b-nav-item>
      <b-nav-item href="#">About</b-nav-item>
      <b-nav-item href="#">Portfolio</b-nav-item>
      <b-nav-item href="#">Contact</b-nav-item>
    </b-navbar-nav>
    </b-navbar-nav>
  </b-collapse>
</b-navbar>

<!-- navbar-1.vue -->
</template>
<script>
export default {};
</script>

<style>
.navbar-dark .navbar-brand {
  color: #32383e;
}
ul.navbar-nav {
  color: blue !important;
}
</style>
