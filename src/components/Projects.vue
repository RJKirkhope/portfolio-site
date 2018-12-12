<template>
<div>
  <div class="project">
    <div class="projects-transparent">
        <h1 class="projects-header">Recent Projects</h1>
      <div class="project-content">
    <a href="https://travelbug-groupproject.firebaseapp.com/">TravelBug Group Project.</a>
    <p>A four day group project that required a new team to build a functioning app in a framework none of us had ever touched(Vue).</p>
    <a href="https://hangrygirlfriend-e7cf0.firebaseapp.com/">Hangry Girlfriend App</a>
    <p>A functioning CRUD app that helps users decide where they want to go for dinner.</p>
    <a href="https://github.com/RJKirkhope/CapstoneAPP">Garage Manager</a>
    <p>A react native site that allows DIY users to manage the consumables used in maintaining their vehicles.</p>
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
  padding-top: 15vh;
}
.projects-transparent{
  border: 1px solid black;
  border-radius: 10px;
  height: 70vh;
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
}
@media only screen and (max-width: 400px){
  .project{
    padding-top: 5vh;
  }
  .project-content{
    font-size: 12pt;
    margin-left: 1vw;
    margin-right: 1vw;
  }
  .projects-transparent{
    height: 90vh;
  }
}
</style>