<template>
<div>
  <h1>Recent Projects</h1>
  <div class="project-content">
    <div class="projects">
    <a href="https://travelbug-groupproject.firebaseapp.com/">TravelBug Group Project.</a>
    <p>A four day group project that required a new team to build a functioning app in a framework none of us had ever touched(Vue).</p>
    <a href="https://hangrygirlfriend-e7cf0.firebaseapp.com/">Hangry Girlfriend App</a>
    <p>A functioning CRUD app that helps users decide where they want to go for dinner.</p>
    <a href="https://github.com/RJKirkhope/CapstoneAPP">Garage Manager</a>
    <p>A react native site that allows DIY users to manage the consumables used in maintaining their vehicles.</p>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name:'Projects'
}
</script>

<style>
.project-content{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
</style>