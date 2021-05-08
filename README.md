# UTS_PemrogramanWeb
~~~
Nama    : Arif Samsudin
NIM     : 311910255
Kelas   : TI.19.C1
UTS Praktikum Pemograman Web
~~~
# 1. Mencari Referensi
 Mencari mockup/sketsa desain web (dalam format psd, png, cdr, svg, dll)
Link Source https://www.free-css.com/free-css-templates
 ![1  persiapan](https://user-images.githubusercontent.com/81839328/117522364-28148a00-afdd-11eb-80c7-23de6537267b.PNG)

# 2. Download Mockup Design. 
Mockup Source https://www.free-css.com/free-css-templates/page266/data-web
![2  Pilih tema](https://user-images.githubusercontent.com/81839328/117522438-96f1e300-afdd-11eb-9693-dff126ef6907.PNG)

# 3. Extract File
Extract file yang sudah didownload, cari file dengan ext .HTML untuk mengambil source dan ext .css untuk mengambil file css
![3  Extrack](https://user-images.githubusercontent.com/81839328/117522526-2e573600-afde-11eb-9c6e-e74013c86b10.PNG)
![3  html](https://user-images.githubusercontent.com/81839328/117522529-3020f980-afde-11eb-88b5-e05cc8f88772.PNG)
![3  css](https://user-images.githubusercontent.com/81839328/117522530-30b99000-afde-11eb-9549-c4c0f9de6468.PNG)

# 4. Buka Source Code di Visual Code
# Source HTML
~~~
<!DOCTYPE html>
<html lang="en">
   <head>
      <!-- basic -->
      <meta charset="utf-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- mobile metas -->
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <meta name="viewport" content="initial-scale=1, maximum-scale=1">
      <!-- site metas -->
      <title>Data web</title>
      <meta name="keywords" content="">
      <meta name="description" content="">
      <meta name="author" content="">
      <!-- bootstrap css -->
      <link rel="stylesheet" href="css/bootstrap.min.css">
      <!-- style css -->
      <link rel="stylesheet" href="css/style.css">
      <!-- Responsive-->
      <link rel="stylesheet" href="css/responsive.css">
      <!-- fevicon -->
      <link rel="icon" href="images/fevicon.png" type="image/gif" />
      <!-- Scrollbar Custom CSS -->
      <link rel="stylesheet" href="css/jquery.mCustomScrollbar.min.css">
      <!-- Tweaks for older IEs-->
      <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css">
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fancybox/2.1.5/jquery.fancybox.min.css" media="screen">
      <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script><![endif]-->
   </head>
   <!-- body -->
   <body class="main-layout">
      <!-- loader  -->
      <div class="loader_bg">
         <div class="loader"><img src="images/loading.gif" alt="#" /></div>
      </div>
      <!-- end loader -->
      <!-- header -->
      <header>
         <!-- header inner -->
         <div class="header">
            <div class="container">
               <div class="row">
                  <div class="col-xl-3 col-lg-3 col-md-3 col-sm-3 col logo_section">
                     <div class="full">
                        <div class="center-desk">
                           <div class="logo">
                              <a href="index.html"><img src="images/logo.png" alt="#" /></a>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="col-xl-9 col-lg-9 col-md-9 col-sm-9">
                     <nav class="navigation navbar navbar-expand-md navbar-dark ">
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample04" aria-controls="navbarsExample04" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarsExample04">
                           <ul class="navbar-nav mr-auto">
                              <li class="nav-item active">
                                 <a class="nav-link" href="#">Home</a>
                              </li>
                              <li class="nav-item">
                                 <a class="nav-link" href="#"> About  </a>
                              </li>
                              <li class="nav-item">
                                 <a class="nav-link" href="#service"> Service</a>
                              </li>
                              <li class="nav-item">
                                 <a class="nav-link" href="#contact">Contact</a>
                              </li>
                              <li class="nav-item">
                                 <a class="nav-link" href="#">Sign Up</a>
                              </li>
                           </ul>
                        </div>
                     </nav>
                  </div>
               </div>
            </div>
         </div>
      </header>
      <!-- end header inner -->
      <!-- end header -->
      <!-- banner -->
      <section class="banner_main">
         <div class="container">
            <div class="row d_flex">
               <div class="col-md-5">
                  <div class="text-bg">
                     <h1>Power ful<br> Web Hosting</h1>
                     <span>Landing Page 2019</span>
                     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud </p>
                     <a href="#">Get Started</a>
                  </div>
               </div>
               <div class="col-md-7">
                  <div class="text-img">
                     <figure><img src="images/img.png" /></figure>
                  </div>
               </div>
            </div>
         </div>
      </section>
      <!-- end banner -->
      <!-- Hosting -->
      <div id="" class="hosting">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>What’s New In Web Hosting</h2>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12">
                  <div class="web_hosting">
                     <figure><img  src="images/web.jpg" alt="#"/></figure>
                     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate</p>
                     <a href="#">Read more</a>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end Hosting -->
      <!-- Services  -->
      <div id="service" class="Services">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>Best Services</h2>
                     <p>Lorem ipsum dolor sittem ametamngcing elit, per sed do eiusmoad <br>
                        teimpor sittem elit inuning ut sed.
                     </p>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="Services-box">
                     <i><img src="images/service1.png" alt="#" /></i>
                     <h3> Shared Hosting</h3>
                     <p>Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci.</p>
                  </div>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="Services-box">
                     <i><img src="images/service2.png" alt="#" /></i>
                     <h3>Dedicated Hosting</h3>
                     <p>Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci.</p>
                  </div>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="Services-box">
                     <i><img src="images/service3.png" alt="#" /></i>
                     <h3>Domain Registration</h3>
                     <p>Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci.</p>
                  </div>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="Services-box">
                     <i><img src="images/service4.png" alt="#" /></i>
                     <h3>VPS Hosting</h3>
                     <p>Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci.</p>
                  </div>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="Services-box">
                     <i><img src="images/service5.png" alt="#" /></i>
                     <h3>Cloud Hosting</h3>
                     <p>Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci.</p>
                  </div>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="Services-box">
                     <i><img src="images/service6.png" alt="#" /></i>
                     <h3>Reseller Hosting</h3>
                     <p>Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci.</p>
                  </div>
               </div>
               <a class="read_more" href="#">Read More</a>
            </div>
         </div>
      </div>
      <!-- end Servicess -->
      <!-- why -->
      <div id="why" class="why">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>Why you should choose </h2>
                     <p>making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still </p>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div id="box_ho" class="why-box">
                     <i><img src="images/why1.png" alt="#" /></i>
                     <h3>Powerful Features</h3>
                     <p>making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still </p>
                  </div>
                  <a class="read_more bg" href="#">Read More</a>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="why-box">
                     <i><img src="images/why2.png" alt="#" /></i>
                     <h3>Totaly Optimised</h3>
                     <p>making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still </p>
                  </div>
                  <a class="read_more bg" href="#">Read More</a>
               </div>
               <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12">
                  <div class="why-box">
                     <i><img src="images/why3.png" alt="#" /></i>
                     <h3>Worldwide Support</h3>
                     <p>making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still </p>
                  </div>
                  <a class="read_more bg" href="#">Read More</a>
               </div>
            </div>
         </div>
      </div>
      <!-- end why -->
      <!-- contact -->
      <div id="contact" class="contact">
         <div class="container">
            <div class="row">
               <div class="col-md-6 offset-md-3 ">
                  <form class="main_form">
                     <div class="row">
                        <div class="col-sm-12">
                           <input class="contactus" placeholder="Name" type="text" name="Name">
                        </div>
                        <div class="col-sm-12">
                           <input class="contactus" placeholder="Email" type="text" name=" Email">
                        </div>
                        <div class="col-sm-12">
                           <input class="contactus" placeholder="Phone" type="text" name="Phone">
                        </div>
                        <div class="col-sm-12">
                           <textarea class="textarea" placeholder="Message" type="text" name="Message"></textarea>
                        </div>
                        <div class="col-sm-12">
                           <button class="send">Send</button>
                        </div>
                     </div>
                  </form>
               </div>
            </div>
         </div>
      </div>

      <!-- end contact -->
      <!--  footer -->
      <footer>
         <div class="footer">
            <div class="container">
               <div class="row">
                  <div class="col-md-10 offset-md-1">
                     <div class="cont">
                        <h3>Contact now</h3>
                        <span>Free Multipurpose Responsive Landing Page 2019</span>
                        <p>sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, 
                           quissed do eiusmod tempor incididunt ut labore et dolore 
                           magna aliqua. Ut enim ad minim veniam, quis  
                        </p>
                     </div>
                  </div>
               </div>
            </div>
            <div class="copyright">
               <div class="container">
                  <div class="row">
                     <div class="col-md-12">
                        <p>© 2019 All Rights Reserved. <a href="https://html.design/">Free html Templates</a></p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
    
      </footer>
      <!-- end footer -->
      <!-- Javascript files-->
      <script src="js/jquery.min.js"></script>
      <script src="js/popper.min.js"></script>
      <script src="js/bootstrap.bundle.min.js"></script>
      <script src="js/jquery-3.0.0.min.js"></script>
      <script src="js/plugin.js"></script>
      <!-- sidebar -->
      <script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
      <script src="js/custom.js"></script>
      <script src="https:cdnjs.cloudflare.com/ajax/libs/fancybox/2.1.5/jquery.fancybox.min.js"></script>
   </body>
</html>
~~~

# Source CSS
~~~


/*--------------------------------------------------------------------- File Name: style.css ---------------------------------------------------------------------*/


/*--------------------------------------------------------------------- import Fonts ---------------------------------------------------------------------*/

@import url('https://fonts.googleapis.com/css?family=Rajdhani:300,400,500,600,700');
@import url('https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i');

/*****---------------------------------------- 1) font-family: 'Rajdhani', sans-serif;
 2) font-family: 'Poppins', sans-serif;
 ----------------------------------------*****/


/*--------------------------------------------------------------------- import Files ---------------------------------------------------------------------*/

@import url(animate.min.css);
@import url(normalize.css);
@import url(meanmenu.css);
@import url(owl.carousel.min.css);
@import url(slick.css);
@import url(jquery-ui.css);
@import url(nice-select.css);

/*--------------------------------------------------------------------- skeleton ---------------------------------------------------------------------*/

* {
     box-sizing: border-box !important;
}

html {
     scroll-behavior: smooth;
}

body {
     color: #666666;
     font-size: 14px;
     font-family: 'Roboto', sans-serif;
     line-height: 1.80857;
     font-weight: normal;
}

a {
     color: #1f1f1f;
     text-decoration: none !important;
     outline: none !important;
     -webkit-transition: all .3s ease-in-out;
     -moz-transition: all .3s ease-in-out;
     -ms-transition: all .3s ease-in-out;
     -o-transition: all .3s ease-in-out;
     transition: all .3s ease-in-out;
}

h1,
h2,
h3,
h4,
h5,
h6 {
     letter-spacing: 0;
     font-weight: normal;
     position: relative;
     padding: 0 0 10px 0;
     font-weight: normal;
     line-height: normal;
     color: #111111;
     margin: 0
}

h1 {
     font-size: 24px
}

h2 {
     font-size: 22px
}

h3 {
     font-size: 18px
}

h4 {
     font-size: 16px
}

h5 {
     font-size: 14px
}

h6 {
     font-size: 13px
}

*,
*::after,
*::before {
     -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
     box-sizing: border-box;
}

h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
     color: #212121;
     text-decoration: none!important;
     opacity: 1
}

button:focus {
     outline: none;
}

ul,
li,
ol {
     margin: 0px;
     padding: 0px;
     list-style: none;
}

p {
     margin: 0px;
     font-weight: 300;
     font-size: 15px;
     line-height: 24px;
}

a {
     color: #222222;
     text-decoration: none;
     outline: none !important;
}

a,
.btn {
     text-decoration: none !important;
     outline: none !important;
     -webkit-transition: all .3s ease-in-out;
     -moz-transition: all .3s ease-in-out;
     -ms-transition: all .3s ease-in-out;
     -o-transition: all .3s ease-in-out;
     transition: all .3s ease-in-out;
}

img {
     max-width: 100%;
     height: auto;
}

 :focus {
     outline: 0;
}

.btn-custom {
     margin-top: 20px;
     background-color: transparent !important;
     border: 2px solid #ddd;
     padding: 12px 40px;
     font-size: 16px;
}

.lead {
     font-size: 18px;
     line-height: 30px;
     color: #767676;
     margin: 0;
     padding: 0;
}

.form-control:focus {
     border-color: #ffffff !important;
     box-shadow: 0 0 0 .2rem rgba(255, 255, 255, .25);
}

.navbar-form input {
     border: none !important;
}

.badge {
     font-weight: 500;
}

blockquote {
     margin: 20px 0 20px;
     padding: 30px;
}

button {
     border: 0;
     margin: 0;
     padding: 0;
     cursor: pointer;
}

.full {
     float: left;
     width: 100%;
}

.layout_padding {
     padding-top: 90px;
     padding-bottom: 90px;
}

.layout_padding_2 {
     padding-top: 75px;
     padding-bottom: 75px;
}

.light_silver {
     background: #f9f9f9;
}

.theme_bg {
     background: #38c8a8;
}

.margin_top_30 {
     margin-top: 30px !important;
}

.full {
     width: 100%;
     float: left;
     margin: 0;
     padding: 0;
}


/**-- heading section --**/


/*---------------------------- preloader area ----------------------------*/

.loader_bg {
     position: fixed;
     z-index: 9999999;
     background: #fff;
     width: 100%;
     height: 100%;
}

.loader {
     height: 100%;
     width: 100%;
     position: absolute;
     left: 0;
     top: 0;
     display: flex;
     justify-content: center;
     align-items: center;
}

.loader img {
     width: 280px;
}


/*-- navigation--*/

.navigation.navbar {
     float: right;
}

.navigation.navbar-dark .navbar-nav .nav-link {
     padding: 0 25px;
     color: #fff;
     font-size: 16px;
     line-height: 20px;
}

.navigation.navbar-dark .navbar-nav .nav-link:focus,
.navigation.navbar-dark .navbar-nav .nav-link:hover {
     color: #fdd430;
}

.navigation.navbar-dark .navbar-nav .active>.nav-link,
.navigation.navbar-dark .navbar-nav .nav-link.active,
.navigation.navbar-dark .navbar-nav .nav-link.show,
.navigation.navbar-dark .navbar-nav .show>.nav-link {
     color: #fdd430;
}


/*-- header area --*/


/*--------------------------------------------------------------------- top banner area ---------------------------------------------------------------------*/


/*--------------------------------------------------------------------- layout new css ---------------------------------------------------------------------*/

.header {
     background: #0c0f38;
     width: 100%;
     padding: 40px 40px 40px 40px;
}

.logo a {
     font-size: 40px;
     font-weight: bold;
     text-transform: uppercase;
     color: #fff;
     line-height: 40px;
}

.banner_main {
     background: #0c0f38;
     background-size: 100% 100%;
     background-repeat: no-repeat;
     padding-bottom: 90px;
}

.text-bg h1 {
     color: #fff;
     font-size: 60px;
     line-height: 80px;
     padding-bottom: 25px;
     font-weight: bold;
}

.text-bg span {
     color: #fdd430;
     font-size: 40px;
     line-height: 35px;
     font-weight: bold;
}

.text-bg p {
     color: #fff;
     font-size: 17px;
     line-height: 28px;
     padding: 40px 0;
}

.text-bg a {
     font-size: 16px;
     background-color: #fff;
     color: #000;
     padding: 10px 0px;
     width: 100%;
     max-width: 190px;
     text-align: center;
     display: inline-block;
     text-transform: uppercase;
}

.text-bg a:hover {
     background-color: #000;
     color: #fff;
}

.text-img figure {
     margin: 0px;
}

.text-img figure img {
     width: 100%;
}

.titlepage {
     text-align: center;
     padding-bottom: 60px;
}

.titlepage h2 {
     font-size: 45px;
     color: #0c0f38;
     line-height: 40px;
     font-weight: bold;
     padding: 0;
}


/** Hosting section **/

.hosting {
     padding-top: 90px;
}

.web_hosting {
     text-align: center;
}

.web_hosting figure {
     margin: 0;
}

.web_hosting p {
     color: #0c0f38;
     font-size: 17px;
     line-height: 28px;
     padding: 40px 50px;
}

.web_hosting a {
     font-size: 16px;
     background-color: #000;
     color: #fff;
     padding: 10px 0px;
     width: 100%;
     max-width: 190px;
     text-align: center;
     display: inline-block;
     text-transform: uppercase;
     font-weight: 400;
     margin-top: 10px;
}

.web_hosting a:hover {
     background-color: #0c0f38;
     color: #fff;
}


/** end Hosting section **/


/** Services section **/

.Services {
     margin-top: 90px;
     padding: 60px 0;
     background: #0c0f38;
     font-family: Poppins;
}

.Services .titlepage {
     text-align: center;
}

.Services .titlepage h2 {
     color: #fff;
     padding-bottom: 20px;
}

.Services .titlepage p {
     color: #fff;
}

.Services .Services-box i {
     background: #fff;
     width: 100px;
     height: 100px;
     border-radius: 50px;
     display: inline-block;
     padding-top: 19px;
}

.Services .Services-box i:hover {
     background: #ddd;
}

.Services .Services-box h3 {
     padding: 20px 0px 20px 0px;
     font-size: 20px;
     line-height: 25px;
     color: #fff;
     display: block;
     font-weight: 500;
}

.Services .Services-box {
     text-align: center;
     background-color: transparent;
     border-radius: 20px;
     border: #cecfd7 solid 2px;
     padding: 40px;
     transition: ease-in all 0.5s;
     margin-bottom: 30px;
}

.Services .Services-box:hover {
     background: #8308eb;
     transition: ease-in all 0.5s;
     cursor: pointer;
}

.Services .Services-box p {
     font-size: 16px;
     line-height: 24px;
     color: #fff;
}

.read_more {
     font-size: 16px;
     background-color: #fff;
     color: #000;
     padding: 10px 0px;
     width: 100%;
     max-width: 190px;
     display: flex;
     justify-content: center;
     text-align: center;
     margin: 0 auto;
     margin-top: 20px;
}

.read_more:hover {
     background: #8308eb;
     color: #fff;
}


/** end Services section **/


/** why section **/

.why {
     margin-top: 90px;
     background: #ffff;
     font-family: Poppins;
}

.why .titlepage {
     text-align: center;
}

.why .titlepage h2 {
     padding-bottom: 20px;
}

.why .titlepage p {
     color: #090808;
}

.why .why-box h3 {
     padding: 20px 0px 20px 0px;
     font-size: 20px;
     line-height: 25px;
     color: #090808;
     display: block;
     font-weight: 500;
}

.why .why-box {
     text-align: center;
     background-color: transparent;
     border-radius: 20px;
     padding: 40px 20px 20px 20px;
     transition: ease-in all 0.5s;
     margin-bottom: 30px;
     box-shadow: #ddd 0px 0px 10px
}

.why .why-box p {
     font-size: 16px;
     line-height: 24px;
     color: #090808;
}

.why .why-box:hover {
     transition: ease-in all 0.1s;
     transform: scale(1.1);
}

.bg {
     font-size: 16px;
     background-color: #090808;
     color: #fff;
     padding: 10px 0px;
     width: 100%;
     max-width: 190px;
     display: flex;
     justify-content: center;
     text-align: center;
     margin: 0 auto;
     margin-top: 20px;
}

.bg:hover {
     background: #8308eb;
     color: #fff;
}


/** end why section **/


/** contact section **/

.contact {
     padding-top: 90px;
     font-family: Poppins;
}

.main_form {
     background: #0c0f38;
     padding: 55px 55px;
     border-radius: 30px;
     margin-bottom: -58%;
}

.contact .main_form .contactus {
     border: #fff solid 1px;
     padding: 0px 19px;
     margin-bottom: 20px;
     border-radius: 15px;
     width: 100%;
     height: 52px;
     background: #fff;
     color: #999999;
     font-size: 16px;
}

.contact .main_form .textarea {
     margin-bottom: 25px;
     padding: 0px 19px;
     color: #999999 !important;
     width: 100%;
     border: #fff solid 1px;
     border-radius: 15px;
     padding-top: 38px;
     background: #fff;
}

.contact .main_form .send {
     font-size: 16px;
     transition: ease-in all 0.5s;
     background-color: #fff;
     color: #ef4259;
     padding: 12px 70px;
     margin: 0 auto;
     display: block;
     border-radius: 30px;
}

.contact .main_form .send:hover {
     background-color: #8308eb;
     transition: ease-in all 0.5s;
     color: #fff;
}

#contact *::placeholder {
     color: #999999;
     opacity: 1;
}

.current {
     color: #fff;
     margin-top: -4px;
     position: absolute;
}


/** end contact section **/


/** footer **/

.footer {
     font-family: Poppins;
     background: #0c0f38;
}

.cont {
     text-align: center;
     margin-top: 31%;
}

.cont h3 {
     color: #fff;
     font-size: 45px;
     line-height: 30px;
     font-weight: bold;
     padding: 30px 0px 0px 0px;
}

.cont span {
     color: #fff;
     font-size: 30px;
     line-height: 30px;
     padding: 30px 0px 30px 0px;
     display: inline-block;
     font-weight: bold;
}

.cont p {
     color: #fff;
     font-size: 17px;
     line-height: 30px;
     padding: 0 130px;
     padding-bottom: 60px;
}

.copyright {
     padding: 20px 0px;
     background: #fff;
}

.copyright p {
     color: #1e1e1e;
     font-size: 18px;
     line-height: 22px;
     text-align: center;
}

.copyright a {
     color: #1e1e1e;
}

.copyright a:hover {
     color: #0c0f38;
}


/** end footer **/


~~~
![4  Source](https://user-images.githubusercontent.com/81839328/117522559-59418a00-afde-11eb-9ba8-65821ce696d5.PNG)

# 5. Hasil Convert
![5  Hasil](https://user-images.githubusercontent.com/81839328/117522665-d40aa500-afde-11eb-933c-54892443826d.PNG)

