<template>
  <div id="app">
    <nav>
        
          <router-link to="/" class="nav-link active">Home</router-link>|
    <router-link to="/about" class="nav-link ">About</router-link>|
          <router-link to="/services" class="nav-link">Services</router-link>|
          <router-link to="/porfolio" class="nav-link ">Porfolio</router-link>|
          <router-link to="/resume" class="nav-link">Resume</router-link>|
          <router-link to="/contact" class="nav-link">Contact</router-link>
        
      </nav>
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
