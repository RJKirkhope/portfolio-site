<template>
<div>
  <div class="project">
    <div class="projects-transparent">
      <div class="project-content">
        <h1 class="projects-header">Recent Projects</h1>
    <a href="https://github.com/RJKirkhope/TravelBug-FE">TravelBug Group Project.</a>
    <p>A four day group project that required a new team to build a functioning app in a framework none of us had ever touched(Vue). I was responsible for the google map integration and functionality.</p>
    <a href="https://hangrygirlfriend-e7cf0.firebaseapp.com/">Hangry Girlfriend App</a>
    <p>A functioning CRUD app that helps users decide where they want to go for dinner. Built using Javascript for the front end, and Knex/node.js for the back end.</p>
    <a href="https://github.com/RJKirkhope/CapstoneAPP">Garage Manager</a>
    <p>A React Native app built in 10 days with no previous knowledge of react native. App is
designed to help the user keep track of consumables for DIY motorcycle maintenance.
Uses asynchronous data storage so it can be used even when off network.</p>
    </div>
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
.project{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  width: 100vw;
  height: 100vh;
}
.projects-transparent{
  border: 1px hidden black;
  height: 100vh;
  width: 80vw;
  background-color:rgba(245, 240, 239, 0.8);
}
.project-content{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  font-size: 18pt;
  padding-top: 10vh;
}
@media only screen and (max-width: 400px){

  .project-content{
    font-size: 12pt;
    margin-left: 1vw;
    margin-right: 1vw;
  }
  .projects-transparent{
    height: 100vh;
  }
}
</style>