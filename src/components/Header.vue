<template>
  <div class="header-container">
    <div class = "header-transparent">
      <div class="header-content">
    <h1>R.J. Kirkhope</h1>
    <h2>Full-Stack Web Developer</h2>
    <img class="header-img" src="../assets/rj.png" alt="RJ Kirkhope">
  </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
.header-container{
padding-top: 15vh;
height: 9vh;
padding-bottom: 10vh;
}
.header-content{
margin-left: 2vw;
margin-right: 2vw;
}
.header-img{
  display: none;
}
.header-transparent{
border: 1px solid black;
  border-radius: 10px;
  margin-left: 2vw;
  margin-right: 10vw;
  background-color:rgba(245, 240, 239, 0.8);
}
@media only screen and (max-width: 400px){
.header-img{
display:flex;
height: 35vh;
width: 40vw;
margin-left: 18vw;
margin-top: 5vh;
border-radius: 50%;
}
.header-transparent{
  height: 90vh;
  width: 80vw;
}
.header-container{
padding-top: 5vh;
margin-left: 7vw;
}
}
</style>