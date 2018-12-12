<template>
  <div class="about">
    <div class="transparent-about">
    <div class="about-description">
    <h1>About me.</h1>
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
  padding-top: 15vh;
}
.transparent-about{
  display: flex;
  flex-direction: row;
border: 1px solid black;
  border-radius: 10px;
  padding-left: 2vw;
  padding-right: 2vw;
  margin-right: 2vw;
  margin-left: 2vw;
  height: 70vh;
  width: 80vw;
  background-color:rgba(245, 240, 239, 0.8);
}
.about-img{
height: 45vh;
width: 35vw;
margin-top: 10vh;
margin-left: 3vw;
border-radius: 50%;
}
.about-description{
  display: flex;
  flex-direction: column;
  height: 40vh;
  width: 45vw;
}
@media only screen and (max-width: 400px){
.about{
  padding-top: 5vh;
}
.transparent-about{
  height: 90vh;
}
.about-img{
  display: none;
}
.description{
    margin-left: 1vw;
    margin-right: 1vw;
}
.paragraph{
  width: 78vw;
}
}
</style>