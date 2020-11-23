<template>
  <div id="nav">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
        <router-link class="nav-item nav-link" to="/">Home</router-link> 
        <router-link class="nav-item nav-link" to="/contacto">Contacto</router-link> 
        <router-link class="nav-item nav-link" to="/usuarios">Usuarios</router-link> 
        <router-link class="nav-item nav-link" to="/productos">Productos</router-link> 
        <router-link class="nav-item nav-link" to="/login">Login</router-link> 
        <router-link class="nav-item nav-link" to="/about">About</router-link> 
         <!-- <router-link class="nav-item nav-link" to="/signup">SignUp</router-link> 
         <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
          <a class="nav-item nav-link" href="#">Features</a>
          <a class="nav-item nav-link" href="#">Pricing</a>
          <a class="nav-item nav-link disabled" href="#">Disabled</a> -->
        </div>
      </div>
    </nav>
  </div>
  <router-view/>
</template>

<script>
import "../node_modules/bootstrap/dist/js/bootstrap.min.js";
export default {
  
}
</script>

<style>
@import "../node_modules/bootstrap/dist/css/bootstrap.min.css";

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
