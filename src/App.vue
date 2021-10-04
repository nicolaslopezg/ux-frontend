<template>
  <div id="app" >
    <Navbar></Navbar>
    <Home/>
    <Footer/>
    
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Home,
    Navbar,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
 
}

body {
 background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(248, 230, 180, 0.5)), url("https://i.ibb.co/vJNJVd7/1593870889167.jpg");
 background-repeat: no-repeat;
 background-attachment: fixed;
 background-size: cover;
 
}


</style>
