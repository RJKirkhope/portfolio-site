<template>
  <div id="app">
    <Header />
    <About />
    <Skills />
    <Projects />
    <Contact />
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
  color: #2c3e50;
  margin-top: 60px;
}
</style>
