<template>
  <div class="horizontal-scroll" id="app">
    <Header class="card"/>
    <About class="card"/>
    <Skills class="card"/>
    <Projects class="card"/>
    <Contact class="card"/>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header'
import About from './components/About'
import Skills from './components/Skills'
import Projects from './components/Projects'
import Contact from './components/Contact'
export default {
  name: 'App',
  components: {
    Header,
    About,
    Skills,
    Projects,
    Contact
  }

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(3, 42, 54);
  height: 100vh;
  width: 100vw;
}
@media only screen and (max-width: 400px) {
  #app {
    background-image: url(assets/background.jpeg);
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
  }
}
.horizontal-scroll {
  display: flex;
  flex-wrap: nowrap;
  overflow-x: auto;
  background-size: cover;
  background-image: url(assets/background.jpeg);
}
  .card {
    flex: 0 0 auto;
  }

</style>
