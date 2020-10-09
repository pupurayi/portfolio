<template>
  <div id="app">
   <!--about section, a vue component -->
<About></About> 
<!--project -->
<Projects></Projects>
 <!-- Study-->
 <Study></Study>
   
 <!--Inspiration -->
 <Inspiration></Inspiration>
 <!--the other part-->
  <Other></Other>
  <!--Fotter part-->
  <Footer></Footer>
 <a href="#top">Top</a>

  </div>
</template>

<script>
import Other from './components/Other.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Study from './components/Study.vue'
import Inspiration from './components/Inspiration.vue'

export default {
  name: 'App',
  components:{
    About,
    Projects,
    Study,
    Inspiration,
    Other,
    
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
