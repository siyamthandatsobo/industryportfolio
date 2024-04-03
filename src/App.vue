<template>
  <div id="app">
    <nav id="navbar" class="navbar container">
        <ul>
          <li><router-link to="/" class="nav-link active">Home</router-link></li>
          <li><router-link to="/about" class="nav-link ">About</router-link></li>
          <li><router-link to="/services" class="nav-link">Services</router-link></li>
          <li><router-link to="/porfoilio" class="nav-link ">Projects</router-link></li>
          <li><router-link to="/resume" class="nav-link">Education&Experience</router-link></li>
          <li><router-link to="/contact" class="nav-link">Contact</router-link></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import '/src/assets/css/style.css';

/* Your global styles here */
</style>
