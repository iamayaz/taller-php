<template lang="html">
  <div>
    <!-- Full Width Image Header -->
    <header class="header-image">
      <div class="headline">
        <div class="container">
          <h1>One Page Wonder</h1>
          <h2>Will Knock Your Socks Off</h2>
        </div>
      </div>
    </header>

    <!-- Page Content -->
    <div class="container">

      <hr class="featurette-divider">

      <!-- First Featurette -->
      <div class="featurette" id="about">
        <img class="featurette-image img-circle img-responsive pull-right" src="http://placehold.it/500x500">
        <h2 class="featurette-heading">This First Heading
          <span class="text-muted">Will Catch Your Eye</span>
        </h2>
        <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
      </div>

      <hr class="featurette-divider">

      <!-- Second Featurette -->
      <div class="featurette" id="services">
        <img class="featurette-image img-circle img-responsive pull-left" src="http://placehold.it/500x500">
        <h2 class="featurette-heading">The Second Heading
          <span class="text-muted">Is Pretty Cool Too.</span>
        </h2>
        <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
      </div>

      <hr class="featurette-divider">

      <!-- Third Featurette -->
      <div class="featurette" id="contact">
        <img class="featurette-image img-circle img-responsive pull-right" src="http://placehold.it/500x500">
        <h2 class="featurette-heading">The Third Heading
          <span class="text-muted">Will Seal the Deal.</span>
        </h2>
        <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
      </div>

      <hr class="featurette-divider">

      <!-- Footer -->
      <footer>
        <div class="row">
          <div class="col-lg-12">
            <p>Copyright &copy; Your Website 2014</p>
          </div>
        </div>
      </footer>
      
    </div>
  </div>
</template>

<script>
export default {
};
</script>

<style lang="css">
/*
 * Start Bootstrap - One Page Wonder (http://startbootstrap.com/)
 * Copyright 2013-2016 Start Bootstrap
 * Licensed under MIT (https://github.com/BlackrockDigital/startbootstrap/blob/gh-pages/LICENSE)
 */

.header-image {
    display: block;
    width: 100%;
    text-align: center;
    background: url('http://placehold.it/1900x500') no-repeat center center scroll;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    background-size: cover;
    -o-background-size: cover;
}

.headline {
    padding: 120px 0;
}

.headline h1 {
    font-size: 130px;
    background: #fff;
    background: rgba(255,255,255,0.9);
}

.headline h2 {
    font-size: 77px;
    background: #fff;
    background: rgba(255,255,255,0.9);
}

.featurette-divider {
    margin: 80px 0;
}

.featurette {
    overflow: hidden;
}

.featurette-image.pull-left {
    margin-right: 40px;
}

.featurette-image.pull-right {
    margin-left: 40px;
}

.featurette-heading {
    font-size: 50px;
}

footer {
    margin: 50px 0;
}

@media(max-width:1200px) {
    .headline h1 {
        font-size: 140px;
    }

    .headline h2 {
        font-size: 63px;
    }

    .featurette-divider {
        margin: 50px 0;
    }

    .featurette-image.pull-left {
        margin-right: 20px;
    }

    .featurette-image.pull-right {
        margin-left: 20px;
    }

    .featurette-heading {
        font-size: 35px;
    }
}

@media(max-width:991px) {
    .headline h1 {
        font-size: 105px;
    }

    .headline h2 {
        font-size: 50px;
    }

    .featurette-divider {
        margin: 40px 0;
    }

    .featurette-image {
        max-width: 50%;
    }

    .featurette-image.pull-left {
        margin-right: 10px;
    }

    .featurette-image.pull-right {
        margin-left: 10px;
    }

    .featurette-heading {
        font-size: 30px;
    }
}

@media(max-width:768px) {
    .container {
        margin: 0 15px;
    }

    .featurette-divider {
        margin: 40px 0;
    }

    .featurette-heading {
        font-size: 25px;
    }
}

@media(max-width:668px) {
    .headline h1 {
        font-size: 70px;
    }

    .headline h2 {
        font-size: 32px;
    }

    .featurette-divider {
        margin: 30px 0;
    }
}

@media(max-width:640px) {
    .headline {
        padding: 75px 0 25px 0;
    }

    .headline h1 {
        font-size: 60px;
    }

    .headline h2 {
        font-size: 30px;
    }
}

@media(max-width:375px) {
    .featurette-divider {
        margin: 10px 0;
    }

    .featurette-image {
        max-width: 100%;
    }

    .featurette-image.pull-left {
        margin-right: 0;
        margin-bottom: 10px;
    }

    .featurette-image.pull-right {
        margin-bottom: 10px;
        margin-left: 0;
    }
}
</style>
