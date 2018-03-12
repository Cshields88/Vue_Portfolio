<template>
  <b-navbar toggleable="md" type="light" variant="info">

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
.navbar-light .navbar-nav .nav-link {
  /* color: white; */
  /* color: #4e576d; */
  color: var(--mint);
  font-size: 1.25em;
  font-family: var(--headings);
}
.navbar-light .navbar-nav .nav-link:hover {
  /* color: white; */
  /* color: #4e576d; */
  color: var(--mint);
  font-size: 1.25em;
}
.bg-info {
  color: white;
  /* background-color: #4cf7c6 !important; */
  background-color: #505050 !important;
  /* background-color: var(--blue-grey) !important; */
}
.navbar-light .navbar-brand {
  color: var(--mint);
}
</style>
