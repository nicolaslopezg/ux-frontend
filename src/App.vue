<template>
  <div id="app" >
    <NavbarUsuario></NavbarUsuario>
    <Usuario/>
    <Footer/>
    
  </div>
</template>

<script>
/*import Home from './components/Home.vue'*/
//import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import Usuario from './components/Usuario.vue'
import NavbarUsuario from './components/NavbarUsuario.vue'
export default {
  name: 'App',
  components: {
   // Home,
   // Navbar,
    Footer,
    Usuario,
    NavbarUsuario
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
 background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(248, 230, 180, 0.5)), url("https://i.ibb.co/PgnsMfw/best-banks-in-Canada.webp");
 background-repeat: no-repeat;
 background-attachment: fixed;
 background-size: cover;
 
}


</style>
