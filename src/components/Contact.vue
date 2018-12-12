<template>
  <div class="contact">
    
    <div class="transparent-contact">
      <h1 class="contact-header">Contact info.</h1>
    <div class="contact-information">
    <a href="https://www.linkedin.com/in/robert-kirkhope/">Linked-in</a>
    <a href="https://github.com/RJKirkhope">Github</a>
    <a href="https://drive.google.com/file/d/1SG9PtFEC1rqjukUOmOUc3uaOM7te_FLS/view?usp=sharing">Resume</a>
    <p>Email: rjkirkhope@gmail.com</p>
    <p> Phone : 303-717-3002</p>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style>
.contact{
  width: 100vw;
  padding-top: 15vh;
}
.transparent-contact{
border: 1px solid black;
  border-radius: 10px;
  margin-left: 10vw;
  height: 70vh;
  width: 80vw;
  background-color:rgba(245, 240, 239, 0.8);
}
.contact-information{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  font-size: 18pt;
}
@media only screen and (max-width: 400px){
.contact{
  padding-top: 5vh;
}
.transparent-contact{
  height: 90vh;
}
}

</style>


