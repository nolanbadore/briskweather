<!doctype html>
<html class="no-js" lang="">

<head>
  <meta charset="utf-8">
  <title>PhotoWeather</title>
  <meta name="description" content="">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <link rel="manifest" href="site.webmanifest">
  <link rel="apple-touch-icon" href="icon.png">
  <!-- Place favicon.ico in the root directory -->


  <link rel="stylesheet" href="https://use.typekit.net/rfw0oct.css">
  <link rel="stylesheet" href="css/normalize.css">
  <link rel="stylesheet" href="css/main.css">

  <meta name="theme-color" content="#fafafa">
</head>

<body>


<header>

  <img class="hor" src="img/brisk-hor.svg">
  <img class="vert" src="img/brisk-vert.svg">
  
  <p class="message"></p>
  
</header>

<section class="today">
  <article class="main">
    
    <h2>Boston</h2>

    <div class="strokeOne"></div>

    <div class="todayHigh"></div>

    <div class="strokeTwo"></div>
    <div class="todayLow"></div>
    <p class="Low">LOW</p>

  </article>

  <article class="secondary">
    
    <div class="todaySummary"></div>

    <div class="strokeThree"></div>

    <p class="Precip">Precipitation:</p>
    <div class="todayPrecip"></div>

    <p class="Visi">Visibility:</p>
    <div class="todayVisibility"></div>

    <p class="Wind">Wind Speed:</p>
    <div class="todayWindSpeed"></div>

    <p class="Humi">Humidity:</p>
    <div class="todayHumidity"></div>

  </article>
</section>

<section class="sliding-panel">

    <p class="daily">Daily</p>
    <img class="chevron" src="img/chev.svg">
  
  <article class="dailyinfo">
  <section class="dayZero">
    <div class="todayHigh"></div>
    <div class="todaySummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="todayPrecip"></div>
  </section>

  <section class="dayOne">
    <div class="oneHigh"></div>
    <div class="oneSummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="onePrecip"></div>
  </section>

  <section class="dayTwo">
    <div class="twoHigh"></div>
    <div class="twoSummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="twoPrecip"></div>
  </section>

  <section class="dayThree">
    <div class="threeHigh"></div>
    <div class="threeSummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="threePrecip"></div>
  </section>

  <section class="dayFour">
    <div class="fourHigh"></div>
    <div class="fourSummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="fourPrecip"></div>
  </section>

  <section class="dayFive">
    <div class="fiveHigh"></div>
    <div class="fiveSummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="fivePrecip"></div>
  </section>

  <section class="daySix">
    <div class="sixHigh"></div>
    <div class="sixSummary"></div>
    <p class="Precip">Precipitation:</p>
    <div class="sixPrecip"></div>
  </section>

</article>
</section>





























  <script src="js/vendor/modernizr-3.7.1.min.js"></script>
  <script src="https://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>
  <script>window.jQuery || document.write('<script src="js/vendor/jquery-3.3.1.min.js"><\/script>')</script>
  <script src="js/plugins.js"></script>
  <script src="js/main.js"></script>


</body>

</html>
