<template>
  <div id="app">
    <nav id="navbar" class="navbar container" :class="{ 'navbar-mobile': isMobileNavOpen }">
        <ul v-show="!isHomeActive || isMobileNavOpen">
          <li><router-link to="/" class="nav-link" exact active-class="active">Home</router-link></li>
          <li><router-link to="/about" class="nav-link" exact active-class="active">About</router-link></li>
          <li><router-link to="/services" class="nav-link" exact active-class="active">Projects</router-link></li>
          <li><router-link to="/resume" class="nav-link" exact active-class="active">Education&Experience</router-link></li>
          <li><router-link to="/contact" class="nav-link" exact active-class="active">Contact</router-link></li>
        </ul>
        <i class="mobile-nav-toggle bi bi-list" @click="toggleNavbar"></i>
    </nav><!-- .navbar -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      isHomeActive: false,
      isMobileNavOpen: false
    };
  },
  watch: {
    $route(to) {
      // Check if the current route is the home route
      this.isHomeActive = to.path === '/';
    }
  },
  methods: {
    toggleNavbar() {
    this.isMobileNavOpen = !this.isMobileNavOpen;
  }
  }
}
</script>

<style>
@import '/src/assets/css/style.css';

/* Your global styles here */


/* Hide navbar when home page is active */
#navbar.navbar-mobile ul {
  display: block;
}
</style>
