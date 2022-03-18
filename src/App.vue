<template>
  <div id="app" class="bg-dark text-white m-0">
    <div class="container" style="width: 700px;">
      <div class="jumbotron">
        <img src="./assets/logo.png" alt="logo" srcset="" class="img-fluid my-5">
        <h1 class="display-4 mb-4">{{ msg }}</h1>
        <p class="lead mb-4">{{ sub }}</p>
      </div>

      <AboutMe />
      <Education />
      <MySkills />

      <a href="http://lynear24.github.io" class="btn btn-primary btn-lg active m-5" role="button" aria-pressed="true" >link to my website</a>
    </div>
  </div>
</template>

<script>
import AboutMe from "./components/AboutMe.vue";
import Education from "./components/Education.vue";
import MySkills from "./components/MySkills.vue";

export default {
  name: 'app',
  components: {
    Education,
    MySkills,
    AboutMe
},
  data() {
    return {
      msg: 'Nyle Aldrin S. Maliwat',
      sub: 'Aspiring Web Developer and Artist'
    }
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
