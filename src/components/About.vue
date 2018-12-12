<template>
  <div class="about">
    <div class="description">
      <div class="transparent-about">
    <h1>About me.</h1>
    <p> I have worked lots of jobs in many industries, and while most of them provide me with the stressful, hectic whirlwind I thrive in, the vast majority haven’t allowed me to embrace my creative nature. Becoming a full stack developer offers me an opportunity to work in an industry that is all about creative thinking and adapting to new challenges and technologies. I have recently completed the Galvanize web development program, and plan to take what I learned there and use it as a foundation for shaping myself into a skilled, knowledgeable developer. In the coming months I will be on the hunt for a job in the greater Denver metro to meet your needs for front and/or back end development. When I am not coding, I enjoy rock and ice climbing, dual sport motorcycling, and Dungeons and Dragons. Please feel free to check out some of my recent projects. </p>
    </div>
    </div>
    <img class="about-img" src="../assets/rj.png" alt="RJ Kirkhope">
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
  height:80vh;
  width: 100vw;
}
.transparent-about{
border: 1px solid black;
  border-radius: 10px;
  margin-left: 5vw;
  margin-right: 5vw;
  background-color:rgba(245, 240, 239, 0.6);
}
.about-img{
height: 30vw;
width: 45vw;
padding-left: 3vw;
padding-top: 2vh;
padding-right: 2vw;
border-radius: 50%;
}
.description{
  display: flex;
  flex-direction: column;
  height: 30vh;
  width: 45vw;
  padding-left: 1vw;
}
</style>