<a>




     
</a>
<center><img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/profile.png" alt="Profile" width="150" height="150"></center>
<center>
  <a href="https://www.linkedin.com/in/vladimir-sazonov-66247b21a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
    <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/linkedin-icon.png" alt="linkedin" width="36" height="36">
  </a>
  <a href="https://wa.me/+972508150772">
    <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/whatsapp-icon.png" alt="whatsapp" width="36" height="36">
  </a>
  <a href="mailto:vova.sazonovvv@gmail.com">
    <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/gmail-icon.png" alt="gmail" width="36" height="36">
  </a>
</center>
My name is Vladimir Sazonov, a software developer specializing in Unity Engine and exploring backend development using Node.js. Explore my portfolio and connect for potential collaborations.

***

<center>
<iframe width="506" height="285" src="https://www.youtube.com/embed/RWDRQd1MnFw?si=GLzBj1pHYL3E1asc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</center>

<!--
<html>
  <head>
    <title>Slideshow Images</title>
    <style>
      * {
        box-sizing: border-box
      }
      body {
        font-family: Verdana, sans-serif;
        margin: 0
      }
      .mySlides {
        display: none
      }
      img {
        vertical-align: middle;
      }
      .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
      }
      /* Next & previous buttons */
      .prev,
      .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
      }
      /* Position the "next button" to the right */
      .next {
        right: 0;
        border-radius: 3px 0 0 3px;
      }
      /* On hover, add a black background color with a little bit see-through */
      .prev:hover,
      .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
      }
      /* Caption text */
      .text {
        color: #ffffff;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
      }
      /* Number text (1/3 etc) */
      .numbertext {
        color: #ffffff;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
      }
      /* The dots/bullets/indicators */
      .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #999999;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
      }
      .active,
      .dot:hover {
        background-color: #111111;
      }
      /* Fading animation */
      .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
      }
      @-webkit-keyframes fade {
        from {
          opacity: .4
        }
        to {
          opacity: 1
        }
      }
      @keyframes fade {
        from {
          opacity: .4
        }
        to {
          opacity: 1
        }
      }
      /* On smaller screens, decrease text size */
      @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
          font-size: 11px
        }
      }
    </style>
  </head>
  <body>
    <section id="main-content">
      <div class="slideshow-container">
        <div class="mySlides fade">
          <div class="numbertext">1 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_1.png" style="width:100%">
          <div class="text"></div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">2 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_2.png" style="width:100%">
          <div class="text"></div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">3 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_3.png" style="width:100%">
          <div class="text"></div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">4 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_4.png" style="width:100%">
          <div class="text"></div>
        </div>
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
      </div>
      <br>
      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
        <span class="dot" onclick="currentSlide(4)"></span>
      </div>
    </section>
    <script>
      var slideIndex = 1;
      showSlides(slideIndex);
      function plusSlides(n) {
        showSlides(slideIndex += n);
      }
      function currentSlide(n) {
        showSlides(slideIndex = n);
      }
      function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if(n > slides.length) {
          slideIndex = 1
        }
        if(n < 1) {
          slideIndex = slides.length
        }
        for(i = 0; i < slides.length; i++) {
          slides[i].style.display = "none";
        }
        for(i = 0; i < dots.length; i++) {
          dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
      }
    </script>
  </body>
</html>
-->

<html>
  <head>
    <title>Slideshow Images</title>
    <style>
      * {
        box-sizing: border-box
      }
      body {
        font-family: Verdana, sans-serif;
        margin: 0
      }
      .mySlides {
        display: none
      }
      img {
        vertical-align: middle;
      }
      .slideshow-container {
        max-width: 1000px;
        max-height: 285px;
        position: relative;
        margin: auto;
      }
      /* Next & previous buttons */
      .prev,
      .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
      }
      /* Position the "next button" to the right */
      .next {
        right: 0;
        border-radius: 3px 0 0 3px;
      }
      /* On hover, add a black background color with a little bit see-through */
      .prev:hover,
      .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
      }
      /* Caption text */
      .text {
        color: #ffffff;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
      }
      /* Number text (1/3 etc) */
      .numbertext {
        color: #ffffff;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
      }
      /* The dots/bullets/indicators */
      .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #999999;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
      }
      .active,
      .dot:hover {
        background-color: #111111;
      }
      /* Fading animation */
      .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
      }
      @-webkit-keyframes fade {
        from {
          opacity: .4
        }
        to {
          opacity: 1
        }
      }
      @keyframes fade {
        from {
          opacity: .4
        }
        to {
          opacity: 1
        }
      }
      /* On smaller screens, decrease text size */
      @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
          font-size: 11px
        }
      }
    </style>
  </head>
  <body>
    <section id="main-content">
      <div class="slideshow-container">
        <div class="mySlides fade">
          <div class="numbertext">1 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_1.png" style="width:100%">
          <div class="text"></div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">2 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_2.png" style="width:100%">
          <div class="text"></div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">3 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_3.png" style="width:100%">
          <div class="text"></div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">4 / 4</div>
          <img src="https://raw.githubusercontent.com/vovasazonov/portfolio/master/assets/img/projects/count-sheep/market_image_4.png" style="width:100%">
          <div class="text"></div>
        </div>
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
      </div>
      <br>
      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
        <span class="dot" onclick="currentSlide(4)"></span>
      </div>
    </section>
    <script>
      var slideIndex = 1;
      showSlides(slideIndex);
      function plusSlides(n) {
        showSlides(slideIndex += n);
      }
      function currentSlide(n) {
        showSlides(slideIndex = n);
      }
      function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if(n > slides.length) {
          slideIndex = 1
        }
        if(n < 1) {
          slideIndex = slides.length
        }
        for(i = 0; i < slides.length; i++) {
          slides[i].style.display = "none";
        }
        for(i = 0; i < dots.length; i++) {
          dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
      }
    </script>
  </body>
</html>

***
