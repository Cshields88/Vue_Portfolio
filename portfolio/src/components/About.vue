<template>
<div id="about">
    <!-- <img src="http://equifyllc.com/wp-content/uploads/2016/09/headshot-placeholder-300x300.jpg" alt=""> -->
    <h4>Bio</h4>
    <ul>
        <li>Location: Michigan</li>
        <li>Hobbies: Hiking, Camping, Fishing, Cooking</li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
<h4>Skills</h4>
<br>
    <b-progress-bar class="purple" :value="100">HTML</b-progress-bar>
    <b-progress-bar class="purple" :value="80">CSS</b-progress-bar>
    <b-progress-bar class="purple" :value="70">Javascript</b-progress-bar>
    <b-progress-bar class="purple" :value="50" >Vue.JS</b-progress-bar>
  
      <!-- <b-progress class="mt-1" :max='max' show-value>
      <b-progress-bar :value="70" variant="success">Vue.JS</b-progress-bar>
      <b-progress-bar :value="30" variant="warning">Knockout.JS</b-progress-bar>
      <b-progress-bar :value="20*(1.5/10)" variant="danger">Angular.JS</b-progress-bar>
    </b-progress> -->
    <br>
 
   
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
img {
  width: 20%;
}
.purple {
  margin: 10px;
  border: black 1px solid;
  border-radius: 5px;
  width: 50% !important;
  height: 30%;
  background-color: purple;
}
#about {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  flex-direction: row;
  background-color: var(--blue-grey);
  padding: 10px;
  margin-top: 20px;
}
</style>
