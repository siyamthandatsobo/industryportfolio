<template>
  <div>
    <header id="header">
    <div class="container">

      <h1><a href="index.html">Siyamthanda Tsobo</a></h1>
      <!-- Uncomment below if you prefer to use an image logo -->
      <!-- <a href="index.html" class="mr-auto"><img src="assets/img/logo.png" alt="" class="img-fluid"></a> -->
      <h2>I'm a passionate <span>Full-stack developer</span> from Cape Town</h2>

      <nav id="navbar" class="navbar">
        <ul>
          <li><router-link to="/" class="nav-link active">Home</router-link></li>
          <li><router-link to="/about" class="nav-link ">About</router-link></li>
          <li><router-link to="/services" class="nav-link">Services</router-link></li>
          <li><router-link to="/porfoilio" class="nav-link ">Porfolio</router-link></li>
          <li><router-link to="/resume" class="nav-link">Resume</router-link></li>
          <li><router-link to="/contact" class="nav-link">Contact</router-link></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

      <div class="social-links">
        <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
      </div>

    </div>
  </header>
  </div>
</template>

<script>
// @ is an alias to /src


</script>
<style>


</style>