<template>
<div id="about">
   
  <b-media>
    <b-img slot="aside" src="http://equifyllc.com/wp-content/uploads/2016/09/headshot-placeholder-300x300.jpg"  width="300" alt="placeholder" />
      <h5 class="mt-0"> </h5>
      <ul class="mb-0">
        <li><strong>Email: </strong> example@example.com</li>
        <li><strong>Phone: </strong> (777) 777-7777</li>
        <li></li>
        <li><strong>Location:</strong> Michigan</li>
        <li><strong>Hobbies:</strong> Hiking, Fishing, Camping, Cooking</li>
        <li></li>
      </ul>
    </b-media>
<section>
    <!-- <h4>Skills</h4> -->
 <h5>HTML</h5>
    <b-progress :value="90"  show-value class="mb-3"></b-progress>
    <h5>CSS</h5>
    <b-progress :value="85"  show-value class="mb-3"></b-progress>
    <h5>Javascript</h5>
    <b-progress :value="70"  show-value class="mb-3"></b-progress>
    <h5>Vue.JS</h5>
    <b-progress :value="60"  show-value class="mb-3"></b-progress>
</section>
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
ul {
  list-style: none;
}
li {
  font-size: 1.15em;
}
img {
  padding: 20px 0;
}
.purple {
  margin: 10px;
  border: black 1px solid;
  border-radius: 5px;
  width: 50% !important;
  height: 30%;
  background-color: purple;
}
section1 {
  display: flex;
  /* flex-wrap: wrap; */
  justify-content: flex-start;
  flex-direction: row;
  /* background-color: var(--blue-grey); */
  padding: 10px;
  margin-top: 20px;
}
</style>
