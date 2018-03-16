<template>
<div id="about">
    
<h4>Skills</h4>

    <b-progress-bar class="purple" :value="100">HTML</b-progress-bar>
    <b-progress-bar class="purple" :value="80">CSS</b-progress-bar>
    <b-progress-bar class="purple" :value="70">Javascript</b-progress-bar>
    <b-progress-bar class="purple" :value="50" >Vue.JS</b-progress-bar>
  
      <b-progress class="mt-1" :max='max' show-value>
      <b-progress-bar :value="70" variant="success">Vue.JS</b-progress-bar>
      <b-progress-bar :value="30" variant="warning">Knockout.JS</b-progress-bar>
      <b-progress-bar :value="20*(1.5/10)" variant="danger">Angular.JS</b-progress-bar>
    </b-progress>
 
</div>
</template>
<script>
export default {
  data() {
    return {
      max: 100
    };
  }
};
</script>

<style>
.progress-bar {
  /* margin: 10px; */
  /* border: black 1px solid;
  border-radius: 5px;
  background-color: purple; */
}
.purple {
  margin: 10px;
  border: black 1px solid;
  border-radius: 5px;
  background-color: purple;
}
</style>
