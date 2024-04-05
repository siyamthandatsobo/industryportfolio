<template>
  <div>
    <section id="portfolio" class="portfolio">
    <div class="container">

      <div class="section-title">
        <h2>Portfolio</h2>
        <p>My Works</p>
      </div>

      <div class="row">
        <div class="col-lg-12 d-flex justify-content-center">
          <ul id="portfolio-flters">
            <li data-filter="*" class="filter-active">All</li>
            <!-- <li data-filter=".filter-app">App</li>
            <li data-filter=".filter-card">Card</li>
            <li data-filter=".filter-web">Web</li> -->
          </ul>
        </div>
      </div>

      <div class="row portfolio-container">

        <div class="col-lg-4 col-md-6 portfolio-item filter-app">
          <div class="portfolio-wrap">
            <img src="../assets/img/portfolio/Capstone.png" class="img-fluid" alt="">
            <div class="portfolio-info">
              <h4>Final Capstone Project</h4>
              <p>Full-stack Ecommerce</p>
              <div class="portfolio-links">
                <a href="https://github.com/siyamthandatsobo/Capstone" data-gallery="portfolioGallery" class="portfolio-lightbox github" title="App 1"><i class="bi bi-github"></i></a>
                <a href="https://capstone-8566a.web.app/" data-gallery="portfolioDetailsGallery" data-glightbox="type: external" class="portfolio-details-lightbox btn btn-link" title="Portfolio Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4 col-md-6 portfolio-item filter-web">
          <div class="portfolio-wrap">
            <img src="../assets/img/portfolio/kasi eat.png" class="img-fluid" alt="">
            <div class="portfolio-info">
              <h4>Full-stack ecommerce KASI EATS</h4>
              <p>Nodejs</p>
              <div class="portfolio-links">
                <a href="https://github.com/Anathi9/node-EOMP.git" data-gallery="portfolioGallery" class="portfolio-lightbox github" title="Web 3"><i class="bi bi-github"></i></a>
                <a href="https://node-eomp-8ce51.web.app/" data-gallery="portfolioDetailsGallery" data-glightbox="type: external" class="portfolio-details-lightbox btn btn-link" title="Portfolio Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4 col-md-6 portfolio-item filter-app">
          <div class="portfolio-wrap">
            <img src="../assets/img/portfolio/to do list.png" class="img-fluid" alt="">
            <div class="portfolio-info">
              <h4>To do list</h4>
              <p>JAVASCRIPT</p>
              <div class="portfolio-links">
                <a href="https://github.com/siyamthandatsobo/To-do-list.git" data-gallery="portfolioGallery" class="portfolio-lightbox github" title="App 2"><i class="bi bi-github"></i></a>
                <a href="https://siyatodoapp.netlify.app" data-gallery="portfolioDetailsGallery" data-glightbox="type: external" class="portfolio-details-lightbox btn btn-link" title="Portfolio Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div>
        </div>

      

        <div class="col-lg-4 col-md-6 portfolio-item filter-web">
          <div class="portfolio-wrap">
            <img src="../assets/img/portfolio/ecoomerce site.png" class="img-fluid" alt="">
            <div class="portfolio-info">
              <h4> ECOMMERCE</h4>
              <p>HTML AND CSS</p>
              <div class="portfolio-links">
                <a href="https://github.com/siyamthandatsobo/ecommerce.git" data-gallery="portfolioGallery" class="portfolio-lightbox github" title="Web 2"><i class="bi bi-github"></i></a>
                <a href="https://empiresiya.netlify.app" data-gallery="portfolioDetailsGallery" data-glightbox="type: external" class="portfolio-details-lightbox btn btn-link" title="Portfolio Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div>
        </div>

        

        <div class="col-lg-4 col-md-6 portfolio-item filter-card">
          <div class="portfolio-wrap">
            <img src="../assets/img/portfolio/calculator.png" class="img-fluid" alt="">
            <div class="portfolio-info">
              <h4>BASIC CALCULATOR</h4>
              <p>JAVASCRIPT</p>
              <div class="portfolio-links">
                <a href="https://github.com/siyamthandatsobo/Calculator.git" data-gallery="portfolioGallery" class="portfolio-lightbox github" title="Card 1"><i class="bi bi-github"></i></a>
                <a href="https://tsobocalculator.netlify.app" data-gallery="portfolioDetailsGallery" data-glightbox="type: external" class="portfolio-details-lightbox btn btn-link" title="Portfolio Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4 col-md-6 portfolio-item filter-card">
          <div class="portfolio-wrap">
            <img src="../assets/img/portfolio/temperature converter.png" class="img-fluid" alt="">
            <div class="portfolio-info">
              <h4>Temperature Converter</h4>
              <p>Javascript</p>
              <div class="portfolio-links">
                <a href="https://github.com/siyamthandatsobo/temp-conversion.git"  data-gallery="portfolioGallery" class="portfolio-lightbox github" title="Card 3"><i class="bi bi-github"></i></a>
                <a href="https://tsobotemperatureconversion.netlify.app" data-gallery="portfolioDetailsGallery" data-glightbox="type: external" class="portfolio-details-lightbox btn btn-link" title="Portfolio Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div>
        </div>

       

      </div>

    </div>
  </section>
</div>

</template>
<script></script>
<style scoped>
img{
  height:250px;
  width:400px;
}
</style>