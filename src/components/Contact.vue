<template>
  <div class="contact">
    <div class="transparent-contact">
    <div class="contact-information">
      <h1 class="contact-header">Contact Information</h1>
    <a class="anchor" href="https://www.linkedin.com/in/robert-kirkhope/">Linked-in</a>
    <br>
    <a class="anchor" href="https://github.com/RJKirkhope">Github</a>
    <br>
    <a class="anchor" href="https://drive.google.com/file/d/1SG9PtFEC1rqjukUOmOUc3uaOM7te_FLS/view?usp=sharing">Resume</a>
    <p class="email">Email: rjkirkhope@gmail.com</p>
    <p class="phone"> Phone : 303-717-3002</p>
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
  margin-right: 4vw;
}
.transparent-contact{
border: 1px hidden black;
  height: 100vh;
  width: 60vw;
  background-color:rgba(245, 240, 239, 0.9);
}
.contact-information{
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  font-size: 18pt;
  padding-top: 10vh;
}
.anchor{
font-size: 30pt;
color: rgb(3, 42, 54)
}
.phone{
font-size:24pt;
}
.email{
font-size: 24pt;
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


