<template>
<div>
  <div class="skills">
    <div class="transparent">
<h1>Technologies I have worked with.</h1>
    <div class="bank-one">
      <img class="html5" src="../assets/html5.png" alt="html5">
      <img class="css3" src="../assets/css.png" alt="css">
      <img class="javaScript" src="../assets/JavaScript-logo.png" alt="javaScript">
      <img class="vue" src="../assets/logo.png" alt="Vue">
      <img class="react" src="../assets/React.png" alt ="React">
      
    </div>
    <div class="bank-two">
      <img class="postgres" src="../assets/postgreSQL.png" alt="postgres">
      <img class="knex" src="../assets/knex.png" alt="knex">
      <img class="node" src="../assets/nodejs.png" alt="node">
    
    </div>
    <div class="bank-three">
      <img class ="leaflet" src="../assets/Leaflet.png" alt="Leaflet">
      <img class="postman" src="../assets/postman.png" alt="postman">
      <img class="cypress" src="../assets/cypress.png" alt="cypress">
       
    </div>
    <div class="bank-four">
      <img class="heroku" src="../assets/heroku.png" alt="heroku">
      <img class="firebase" src="../assets/firebase.png" alt="firebase">
      <img class="github" src="../assets/github.png" alt="github">

    </div>
  </div>
  </div>
  </div>
</template>

<script>
export default {
  name:'Skills'
}
</script>

<style>
.skills{
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  width: 100vw;
  padding-top: 15vh;
}
.transparent{
border: 1px solid black;
  border-radius: 10px;
  margin-left: 10vw;
  height: 70vh;
  width: 80vw;
  background-color:rgba(245, 240, 239, 0.7);
}
.bank-one{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.bank-two{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-top: 2vh;
}
.bank-three{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-top: 2vh;
}
.bank-four{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-top: 2vh;
}
.html5{
  height: 11vh;
  width: 9vw;
  padding-top: 2vh;
}
.css3{
  height: 10vh;
  width: 6vw;
  padding-top: 3vh;
}
.javaScript{
  height: 10vh;
  width: 7vw;
  padding-top: 3vh;
}
.vue{
  height: 10vh;
  width: 8vw;
  padding-top: 3vh;
}
.postgres{
  height: 10vh;
  width: 9vw;
  padding-top: 3vh;
}
.heroku{
  height: 11vh;
  width: 8vw;
  padding-top: 3vh;
  margin-bottom: 2vh;
}
.cypress{
  height: 5vh;
  width: 17vw;
  padding-top: 3vh;
}
.leaflet{
  height: 5vh;
  width: 17vw;
  padding-top: 3vh;
}
.firebase{
  height: 5vh;
  width: 16vw;
  padding-top: 7vh;
}
.knex{
  height: 5vh;
  width: 14vw;
  padding-top: 7vh;
  padding-right: 1vw;
}
.postman{
  height: 5vh;
  width: 12vw;
  padding-top: 3vh;
}
.node{
  height: 14vh;
  width: 8vw;
}
.github{
  height: 10vh;
  width: 8vw;
  padding-top: 3vh;
  margin-bottom: 1vh;
}
.react{
  margin-left: -4vw;
  height: 12vh;
  width: 10vw;
padding-top: 2vh;
}

</style>