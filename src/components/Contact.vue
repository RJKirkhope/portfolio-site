<template>
  <div class="contact">
    <div class="background-img-contact">
    <div class="transparent-contact">
    <div class="contact-information">
      <h1 class="contact-header">Contact Information.</h1>
    <a href="https://www.linkedin.com/in/robert-kirkhope/">Linked-in</a>
    <br>
    <a href="https://github.com/RJKirkhope">Github</a>
    <br>
    <a href="https://drive.google.com/file/d/1SG9PtFEC1rqjukUOmOUc3uaOM7te_FLS/view?usp=sharing">Resume</a>
    <p>Email: rjkirkhope@gmail.com</p>
    <p> Phone : 303-717-3002</p>
    </div>
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
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  height: 100vh;
  width: 100vw;
}
.transparent-contact{
border: 1px hidden black;
  margin-left: 10vw;
  height: 100vh;
  width: 80vw;
  background-color:rgba(245, 240, 239, 0.8);
}
.background-img-contact{
  background-image: url(../assets/Mountain.jpg);
  width: 100vw;
  height: 100vh;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.contact-information{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  font-size: 18pt;
  padding-top: 10vh;
}
@media only screen and (max-width: 400px){

.transparent-contact{
  height: 100vh;
}
.contact-header{
  font-size: 24pt;
}
}

</style>


