<template>
  <div class="header-container">
    <div class = "header-transparent">
      <div class="header-content">
    <h1>R.J. Kirkhope</h1>
    <h2>Full-Stack Web Developer</h2>
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
.header-transparent{
border: 1px solid black;
  border-radius: 10px;
  margin-left: 2vw;
  margin-right: 10vw;
  background-color:rgba(245, 240, 239, 0.7);
}
</style>