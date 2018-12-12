<template>
<div>
<h1>Technologies I have worked with.</h1>
  <div class="skills">
      <h2>Front End</h2>
    <div class="bank-one">
      <img class="html5" src="../assets/html5.png" alt="html5">
      <img class="css3" src="../assets/download.png" alt="css">
      <img class="javaScript" src="../assets/JavaScript-logo.png" alt="javaScript">
      <img class="vue" src="../assets/logo.png" alt="Vue">
      <img class="react" src="../assets/React.png" alt ="React">
      
    </div>
      <h2>Back End</h2>
    <div class="bank-two">
      <img class="postgres" src="../assets/postgreSQL.png" alt="postgres">
      <img class="knex" src="../assets/knex.png" alt="knex">
      <img class="node" src="../assets/nodejs.png" alt="node">
    
    </div>
    <h2>Testing</h2>
    <div class="bank-three">
      <img class="postman" src="../assets/postman.png" alt="postman">
      <img class="cypress" src="../assets/cypress.png" alt="cypress">
       
    </div>
      <h2>Deployment</h2>
    <div class="bank-four">
      <img class="heroku" src="../assets/heroku.png" alt="heroku">
      <img class="firebase" src="../assets/firebase.png" alt="firebase">
      <img class="github" src="../assets/github.png" alt="github">

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
  padding-top: 1vh; 
}
.bank-one{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  padding-top: 1vh;
}
.bank-two{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  padding-top: 1vh,
}
.bank-three{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  padding-top: 1vh,
}
.bank-four{
  display: flex;
  flex-direction: row;
  padding-top: 1vh;
  justify-content: space-around;
}
.html5{
  height: 22vh;
  width: 18vw;
  padding-top: 3vh;
}
.css3{
  height: 20vh;
  width: 12vw;
  padding-top: 3vh;
}
.javaScript{
  height: 20vh;
  width: 14vw;
  padding-top: 3vh;
}
.vue{
  height: 20vh;
  width: 16vw;
  padding-top: 3vh;
}
.postgres{
  height: 20vh;
  width: 18vw;
  padding-top: 3vh;
}
.heroku{
  height: 22vh;
  width: 16vw;
  padding-top: 3vh;
}
.cypress{
  height: 10vh;
  width: 34vw;
  padding-top: 3vh;
}
.firebase{
  height: 10vh;
  width: 32vw;
  padding-top: 7vh;
}
.knex{
  height: 10vh;
  width: 28vw;
  padding-top: 7vh;
}
.postman{
  height: 10vh;
  width: 24vw;
  padding-top: 3vh;
}
.node{
  height: 28vh;
  width: 16vw;
}
.github{
  height: 20vh;
  width: 16vw;
  padding-top: 1vh;
}
.react{
  margin-left: -4vw;
  height: 24vh;
  width: 20vw;

}

</style>