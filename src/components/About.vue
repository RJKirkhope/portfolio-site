<template>
  <div class="about">
    <div class="transparent-about">
    <div class="about-description">
    <h1 class="about-header">About Me</h1>
    <p class="paragraph"> I have worked lots of jobs in many industries, and while most of them provide me with the stressful, hectic whirlwind I thrive in, the vast majority haven’t allowed me to embrace my creative nature. Becoming a full stack developer offers me an opportunity to work in an industry that is all about creative thinking and adapting to new challenges and technologies. I have recently completed the Galvanize web development program, and plan to take what I learned there and use it as a foundation for shaping myself into a skilled, knowledgeable developer. In the coming months I will be on the hunt for a job in the greater Denver metro to meet your needs for front and/or back end development. When I am not coding, I enjoy rock and ice climbing, dual sport motorcycling, and Dungeons and Dragons. Please feel free to check out some of my recent projects. </p>
    </div>
    <img class="about-img" src="../assets/rj.png" alt="RJ Kirkhope">
    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style>
.about{
  display: flex;
  flex-direction: row;
  align-content: space-between;
  justify-content: space-around;
  width: 100vw;
  margin-right: 5vw;
  margin-left: 10vw
}
.transparent-about{
  display: flex;
  flex-direction: row;
border: 1px hidden black;
  padding-left: 2vw;
  padding-right: 2vw;
  margin-right: 2vw;
  margin-left: 2vw;
  height: 100vh;
  width: 80vw;
  background-color:rgba(245, 240, 239, 0.9);
}
.about-img{
height: 45vh;
width: 35vw;
margin-top: 20vh;
margin-left: 3vw;
border-radius: 50%;
}
.about-description{
  display: flex;
  flex-direction: column;
  height: 40vh;
  width: 45vw;
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  font-size: 18pt;
  padding-top: 10vh;
}
.paragraph{
  font-size: 12pt;
}
@media only screen and (max-width: 400px){

.transparent-about{
  height: 100vh;
}
.about-header{
  font-size: 24pt;
}
.about-img{
  display: none;
}

.paragraph{
  width: 78vw;
}
}
</style>