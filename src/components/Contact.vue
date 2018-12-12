<template>
  <div class="contact">
    <h1>Contact info.</h1>
    <div class="transparent-contact">
    <a href="https://www.linkedin.com/in/robert-kirkhope/">Linked-in</a>
    <a href="https://github.com/RJKirkhope">Github</a>
    <a href="https://drive.google.com/file/d/1SG9PtFEC1rqjukUOmOUc3uaOM7te_FLS/view?usp=sharing">Resume</a>
   <p>Email: rjkirkhope@gmail.com</p>
    <p> Phone : 303-717-3002</p>
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
  padding-top: 5vh;
  width: 100vw;
}
.transparent-contact{
border: 1px solid black;
  border-radius: 10px;
  margin-left: 5vw;
  margin-right: 5vw;
  background-color:rgba(245, 240, 239, 0.6);
}

</style>


