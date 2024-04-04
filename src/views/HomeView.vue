<template>
  <div>
    <header id="header">
    <div class="container">

      <h1><a href="index.html">Siyamthanda Tsobo</a></h1>
      <!-- Uncomment below if you prefer to use an image logo -->
      <!-- <a href="index.html" class="mr-auto"><img src="assets/img/logo.png" alt="" class="img-fluid"></a> -->
      <h2 style=" font-weight: bolder;">I'm a passionate <span>Full-stack developer</span> from Cape Town</h2>

      <nav id="navbar" class="navbar">
        <ul>
          <li><router-link to="/" class="nav-link" exact active-class="active">Home</router-link></li>
          <li><router-link to="/about" class="nav-link" exact active-class="active">About</router-link></li>
          <li><router-link to="/services" class="nav-link" exact active-class="active">Projects</router-link></li>
          <li><router-link to="/resume" class="nav-link" exact active-class="active">Education&Experience</router-link></li>
          <li><router-link to="/contact" class="nav-link" exact active-class="active">Contact</router-link></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav>

      <div class="social-links">
          <!-- GitHub icon -->
          <a href="https://github.com/siyamthandatsobo" class="github"><i class="bi bi-github"></i></a>
          <!-- LinkedIn icon -->
          <a href="https://www.linkedin.com/in/siyamthanda-tsobo-b938bb218/" class="linkedin"><i class="bi bi-linkedin"></i></a>
        </div>
        <div class="overlay-image">

        </div>

    </div>
  </header>
  </div>
</template>

<style scoped>


</style>