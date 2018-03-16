<template>
<div id="about">
    
<h4>Skills</h4>

    <b-progress-bar :value="100">HTML</b-progress-bar>
    <b-progress-bar :value="80">CSS</b-progress-bar>
    <b-progress-bar :value="70">Javascript</b-progress-bar>
    <b-progress-bar :value="50" >Vue.JS</b-progress-bar>
     <b-progress class="mt-1" :max="max" show-value>
      <b-progress-bar :value="60" variant="success">Vue.JS</b-progress-bar>
      <b-progress-bar :value="40" variant="warning">Knockout.JS</b-progress-bar>
      <b-progress-bar :value="" variant="danger"></b-progress-bar>
    </b-progress>
 
</div>
</template>
<script>
export default {};
</script>

<style>
.progress-bar {
  margin: 10px;
  border: black 1px solid;
  border-radius: 5px;
  background-color: purple;
}
</style>
