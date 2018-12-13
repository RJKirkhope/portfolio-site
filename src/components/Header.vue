<template>
  <div class="header-container">
    <div class = "header-transparent">
      <div class="header-content">
    <h1>R.J. Kirkhope</h1>
    <h2>Full-Stack Web Developer</h2>

    <p>Scroll to the right to learn more.</p>
    <div>
    <img class="header-img-mobile" src="../assets/rj.png" alt="RJ Kirkhope">
    <img class="header-img-desktop" src="../assets/motorcycle.jpg" alt="RJ on Motorcycle">
    </div>
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
margin-left: 20vw;
}
.header-content{
margin-left: 2vw;
margin-right: 2vw;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  font-size: 18pt;
  padding-top: 9.2vh;
}
.header-img-desktop{
  height: 54vh;
  width: 54vw;
}
.header-img-mobile{
  display: none;
}
.header-transparent{
border: 1px hidden black;
  margin-left: 2vw;
  margin-right: 5vw;
  height: 100vh;
  background-color:rgba(245, 240, 239, 0.8);
}
@media only screen and (max-width: 400px){
.header-img-mobile{
display:flex;
height: 35vh;
width: 40vw;
margin-left: 18vw;
margin-top: 5vh;
border-radius: 50%;
}
.header-transparent{
  height: 100vh;
  width: 80vw;
}
.header-container{
height: 100vh;
padding-top: 0vh;
padding-bottom: 0vh;
margin-left: 7vw;
}
.header-img-desktop{
display: none;
}
}
</style>