# TheCatmosphere
Getting Started 

 01. All HTML Pages
index.html for Home Page 1
index-2.html for Home Page 2
explore.html for explore nft page
all-author.html for authors Page
all-author-2.html for authors style 2
author.html for author single Page
activity.html for activity Page
item-details.html for nft item details Page
wallet.html for Wallet connect pages
blog.html for Blog Page
blog-2.html for Blog style 2 Page
blog-3.html for Blog style 3 Page
blog-single.html for Blog Details Page
blog-single-2.html for Blog Details style-2 Page
signin.html for Sign In Page
signup.html for Sign Un Page
forgot-pass.html for Forgot password Page
auction.html for Auction Page
contact.html for Contact Us
coming-soon.html for Coming Soon Page
error-page.html for Error Page

 02. Fonts
Go to Google Fonts and select your favorite fonts and then just replace the code in assets/sass/sub-stylesheet/base/fonts.scss file

  <!--Google Fonts-->
      
      @import
      url('https://fonts.googleapis.com/css2?family=Barlow:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');


 03. Source File (CSS)
All required css files have been linked like below-

  <!-- ====== All css file ========= -->
  <link rel="stylesheet" href="assets/css/bootstrap.min.css">
  <link rel="stylesheet" href="assets/css//icofont.min.css">
  <link rel="stylesheet" href="assets/css/lightcase.css">
  <link rel="stylesheet" href="assets/css/animate.css">
  <link rel="stylesheet" href="assets/css/swiper-bundle.min.css">
  <link rel="stylesheet" href="assets/css/style.min.css">

  Source File (SASS)
Here is the SCSS folder structure example-


        *style.scss
              ----sub-stylesheet
                  ----abstracts
                      _mixins.scss
                      _variables.scss
                  
                  ----base
                      _extend.scss
                      _fonts.scss
                      _typography.scss
                  
                  ----components
                      _banner.scss
                      _blog.scss
                      _coming-soon.scss
                      _contact.scss
                      _error-page.scss
                      _footer.scss
                      _global.scss
                      _header.scss
                      _home.scss
                      _item-details.scss
                      _preloader.scss
                      _profile.scss
                      _registration.scss
                      _utilities.scss
                      _widget.scss
                  
                  ----vendors
                      _normalize.scss
                      _rfs.scss

 04. Source File (JS)
All required css files have been linked like below. if you need any customization in JAVASCRIPT you have to edit the function.js file.

  <!-- All Scripts -->
  <script src="assets/js/jquery-3.6.0.min.js"></script>
  <script src="assets/js/bootstrap.bundle.min.js"></script>
  <script src="assets/js/waypoints.min.js"></script>
  <script src="assets/js/lightcase.js"></script>
  <script src="assets/js/swiper-bundle.min.js"></script>
  <script src="assets/js/countdown.min.js"></script>
  <script src="assets/js/jquery.counterup.min.js"></script>
  <script src="assets/js/wow.min.js"></script>
  <script src="assets/js/isotope.pkgd.min.js"></script>
  <script src="assets/js/functions.js"></script>


  Customization

  01. Header Menu
This is site Menu code Pattern, if you wanna change your menu just replace the name of the menu

<div class="header__menu ms-auto">
  <ul class="header__nav mb-0">
    <li class="header__nav-item">
      <a class="header__nav-link active" href="#" role="button"
      data-bs-toggle="dropdown"
      aria-haspopup="true" aria-expanded="false" data-bs-offset="0,10">Home</a>

      <ul class="dropdown-menu header__nav-menu">
        <li><a class="drop-down-item active" href="index.html">Home style 1</a></li>
        <li><a class="drop-down-item" href="index-2.html">Home style 2</a></li>
        <li><a class="drop-down-item" href="coming-soon.html">Home style 3</a></li>
      </ul>
    </li>
    <li class="header__nav-item">
      <a class="header__nav-link" href="#" role="button" data-bs-toggle="dropdown"
      aria-haspopup="true" aria-expanded="false" data-bs-offset="0,10">Explore</a>

      <ul class="dropdown-menu header__nav-menu">
        <li><a class="drop-down-item" href="explore.html">Explore style 1</a></li>
        <li><a class="drop-down-item" href="auction.html">Auction Page</a></li>
        <li><a class="drop-down-item" href="coming-soon.html">Explore style
        2</a></li>
      </ul>
    </li>
    <li class="header__nav-item">
      <a href="activity.html" class="header__nav-link">Activity</a>
    </li>
    <li class="header__nav-item">
      <a class="header__nav-link" href="#" role="button" data-bs-toggle="dropdown"
      aria-haspopup="true" aria-expanded="false" data-bs-offset="0,10">Blog</a>

      <ul class="dropdown-menu header__nav-menu">
        <li><a class="drop-down-item" href="blog.html">Blog style 1</a></li>
        <li><a class="drop-down-item" href="blog-2.html">Blog style 2</a></li>
        <li><a class="drop-down-item" href="blog-3.html">Blog style 3</a></li>
        <li><a class="drop-down-item" href="blog-single.html">Blog Single </a></li>
        <li><a class="drop-down-item" href="blog-single-2.html">Blog Single
        2</a></li>
      </ul>
    </li>
    <li class="header__nav-item">
      <a class="header__nav-link" href="#" role="button" data-bs-toggle="dropdown"
      aria-haspopup="true" aria-expanded="false" data-bs-offset="0,10">Pages</a>

      <ul class="dropdown-menu header__nav-menu">
        <li><a class="drop-down-item" href="item-details.html">NFT Details</a></li>
        <li><a class="drop-down-item" href="all-authors.html">ALL Authors</a></li>
        <li><a class="drop-down-item" href="all-authors-2.html">ALL Authors
        2</a></li>
        <li><a class="drop-down-item" href="author.html">Author Profile</a></li>
        <li><a class="drop-down-item" href="wallet.html">Wallet Connect</a></li>
        <li><a class="drop-down-item" href="404.html">404</a></li>
        <li><a class="drop-down-item" href="forgot-pass.html">Forgot
        Password</a></li>

      </ul>
    </li>
    <li class="header__nav-item">
      <a class="header__nav-link" href="#" role="button" data-bs-toggle="dropdown"
      aria-haspopup="true" aria-expanded="false" data-bs-offset="0,10"><svg
      xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
      <path
      d="M12,10a2,2,0,1,0,2,2A2,2,0,0,0,12,10ZM5,10a2,2,0,1,0,2,2A2,2,0,0,0,5,10Zm14,0a2,2,0,1,0,2,2A2,2,0,0,0,19,10Z"
      />
      </svg></a>

      <ul class="dropdown-menu header__nav-menu">
        <li><a class="drop-down-item" href="contact.html">Contact </a></li>
        <li><a class="drop-down-item" href="coming-soon.html">Coming soon</a></li>
      </ul>
    </li>
  </ul>
</div>
    
To change the menu name you will need to edit in the tag <li><a href="#">menu name </a> </li> and add your text in the middle of the tag.



2. Logo Change
Here is your main logo code. To add your logo, replace logo.png from images/logo/ directory with your logo in PNG format.

  <div class="header__logo">
    <a href="index.html">
      <img src="assets/images/logo/logo.png" alt="logo">
    </a>
  </div>
            
Note: Keep your logo inside the ./assets/images/logo folder. The logo size should be maximum 142x23 pixel.

03.Header Style Changing
If you want to change header style,just add style-2 class in header section .See Belowed example-

  <header class="header style-2">
  ....
  </header>
            

Components customization


01. Section structure
Here is your section structure.

<section class="xyz-section padding-top padding-bottom">
    <div class="container">
        <div class="section-header">
          ....
        </div>
        <div class="section-wrapper">
            <div class="row">
              ....
            </div>
        </div>
    </div>
</section>
    
In the class="xyz-section" you can replace with your desired class.

padding-top is used for the space top of the sections.

padding-bottom is used for the space bottom of the sections.

And in the section-header div you can add your heading of sections and tagline of sections.

You can add your content on the 2nd .section-wrapper div.


2.NFT item coding structure
There is a common markup for the nft-item. You can get different item styles by adding style class to the item or some markup changing. For example, if you want to use the item for auction, it will deal with the list of countdowns, and if you want to see it without auction, it will be commented.

Also, if you add style (for example style-2,style-3,blog-style) utility classes to the nft-item for different styles, you will be able to see different styles (in that case you have to pay attention to the markup).

You can see the example below to be clearer -


Item for auction
  <div class="nft-item">
    <div class="nft-inner">
    <!-- nft top part -->
    <div class="nft-item-top d-flex justify-content-between align-items-center">
      <div class="author-part">
        <ul class="author-list d-flex">
          <li class="single-author">
          <a href="author.html"><img src="assets/images/seller/01.png"
          alt="author-img"></a>
          </li>
          <li class="single-author d-flex align-items-center">
          <a href="#" class="veryfied"><img src="assets/images/seller/01.gif"
          alt="author-img"></a>
            <h6><a href="author.html">Jhon Doe</a></h6>
          </li>
        </ul>
      </div>
      <div class="more-part">
        <div class=" dropstart">
          <a class=" dropdown-toggle" href="#" role="button"
          data-bs-toggle="dropdown" aria-expanded="false"
          data-bs-offset="25,0">
          <i class="icofont-flikr"></i>
          </a>
          
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#"><span>
            <i class="icofont-warning"></i>
            </span> Report </a>
            </li>
            <li><a class="dropdown-item" href="#"><span><i
            class="icofont-reply"></i></span> Share</a></li>
          </ul>
        </div>
      </div>
    </div>

    <!-- nft-bottom part -->
    <div class="nft-item-bottom">
    <div class="nft-thumb">
    <img src="assets/images/nft-item/03.gif" alt="nft-img">
    
      <!-- nft countdwon -->
      <ul class="nft-countdown count-down"
      data-date="July 05, 2022 21:14:01">
        <li>
          <span class="days">34</span><span class="count-txt">D</span>
        </li>
        <li>
          <span class="hours">09</span><span class="count-txt">H</span>
        </li>
        <li>
          <span class="minutes">32</span><span class="count-txt">M</span>
        </li>
        <li>
          <span class="seconds">32</span><span class="count-txt">S</span>
        </li>
      </ul>
    </div>

    <div class="nft-content">
      <h4><a href="item-details.html">Walking On
      Air</a> </h4>
      <div class="price-like d-flex justify-content-between align-items-center">
        <p class="nft-price">Price: <span class="yellow-color">0.34 ETH</span>
        </p>
        <a href="#" class="nft-like theme-color" data-blast="color"><i
        class="icofont-heart"></i>
        230</a>
      </div>
    </div>
    </div>
  </div>
</div>
          

Item for Explore NFT's
  <div class="nft-item">
    <div class="nft-inner">
    <!-- nft top part -->
    <div class="nft-item-top d-flex justify-content-between align-items-center">
      <div class="author-part">
        <ul class="author-list d-flex">
          <li class="single-author">
          <a href="author.html"><img src="assets/images/seller/01.png"
          alt="author-img"></a>
          </li>
          <li class="single-author d-flex align-items-center">
          <a href="#" class="veryfied"><img src="assets/images/seller/01.gif"
          alt="author-img"></a>
            <h6><a href="author.html">Jhon Doe</a></h6>
          </li>
        </ul>
      </div>
      <div class="more-part">
        <div class=" dropstart">
          <a class=" dropdown-toggle" href="#" role="button"
          data-bs-toggle="dropdown" aria-expanded="false"
          data-bs-offset="25,0">
          <i class="icofont-flikr"></i>
          </a>
          
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#"><span>
            <i class="icofont-warning"></i>
            </span> Report </a>
            </li>
            <li><a class="dropdown-item" href="#"><span><i
            class="icofont-reply"></i></span> Share</a></li>
          </ul>
        </div>
      </div>
    </div>

    <!-- nft-bottom part -->
    <div class="nft-item-bottom">
    <div class="nft-thumb">
    <img src="assets/images/nft-item/03.gif" alt="nft-img">
    
    <!-- ===========This part is commented -->

      <!-- nft countdwon -->
      <ul class="nft-countdown count-down"
      data-date="July 05, 2022 21:14:01">
        <li>
          <span class="days">34</span><span class="count-txt">D</span>
        </li>
        <li>
          <span class="hours">09</span><span class="count-txt">H</span>
        </li>
        <li>
          <span class="minutes">32</span><span class="count-txt">M</span>
        </li>
        <li>
          <span class="seconds">32</span><span class="count-txt">S</span>
        </li>
      </ul>

      <!-- ==========Comment end========= -->
    </div>

    <div class="nft-content">
      <h4><a href="item-details.html">Walking On
      Air</a> </h4>
      <div class="price-like d-flex justify-content-between align-items-center">
        <p class="nft-price">Price: <span class="yellow-color">0.34 ETH</span>
        </p>
        <a href="#" class="nft-like theme-color" data-blast="color"><i
        class="icofont-heart"></i>
        230</a>
      </div>
    </div>
    </div>
  </div>
</div>
          

Item style-2
<div class="nft-item style-2">
  <div class="nft-inner">
    <div class="nft-thumb">
      <img src="assets/images/nft-item/style-2/01.jpg" alt="nft-img">
    </div>

    <div class="nft-content">
      <div class="author-thumb">
        <a href="author.html" class="veryfied"><img
      src="assets/images/seller/04.png" alt="author-img"></a>
      </div>
      <div class="author-details">
        <h5><a href="author.html">Gihan Fernindo</a> </h5>
        <p class="nft-price yellow-color">$23,002.98</p>
      </div>
    </div>
  </div>
</div>
          

Item style-3
  <div class="nft-item style-3">
    <div class="nft-inner text-center">
      <div class="nft-thumb">
        <img src="assets/images/nft-item/style-3/01.png" alt="nft-img">
      </div>
      <div class="nft-content">
        <div class="author-details">
          <h4>Set Up Your Wallet</h4>
          <p>Click Create & set up your colecton
          Add social links and a description profile
          banner images and set</p>
        </div>
      </div>
    </div>
  </div>
                              

Item Blog Style
<div class="nft-item blog-item">
  <div class="nft-inner">
    <div class="nft-thumb">
      <img src="assets/images/nft-item/blog/02.jpg" alt="blog-img">
    </div>

    <div class="nft-content">
      <div class="author-details">
        <h4><a href="blog-single.html">The Rise of the Non Fungible Tokens
        (NFTs)</a> </h4>
        <div class="meta-info">
          <p><span><i class="icofont-ui-calendar"
          data-blast="color"></i></span>July 20 2021
          </p>
          <p><span><i class="icofont-user" data-blast="color"></i></span>Jhon
          doe
          </p>
        </div>
      </div>
    </div>
  </div>
</div>
                                          

3.Button Style
There is a different types of button style and hover effect in this template. You can use any of these simple chaning the class name. All button has a default class name called default-btn, beside this class you have to use another class for different hover effect like- move-right, move-left, move-top or move bottom. You also can use different button style by adding style-2 class.

    //======Button style one with differnt hover effect

    //--Hover moving top
    <a href="#" class="default-btn move-top">
      <span>I'm Button</span>
    </a>

    //--Hover moving bottom
    <a href="#" class="default-btn move-bottom">
    <span>I'm Button</span>
    </a>

    //--Hover moving left
    <a href="#" class="default-btn move-left">
    <span>I'm Button</span>
    </a>

    //--Hover moving right
    <a href="#" class="default-btn move-right">
    <span>I'm Button</span>
    </a>




    //======Button style two with differnt hover effect
    
    //--Hover moving top
    <a href="#" class="default-btn style-2 move-top">
    <span>I'm Button</span>
    </a>
    
    //--Hover moving bottom
    <a href="#" class="default-btn style-2 move-bottom">
    <span>I'm Button</span>
    </a>
    
    //--Hover moving left
    <a href="#" class="default-btn style-2 move-left">
    <span>I'm Button</span>
    </a>
    
    //--Hover moving right
    <a href="#" class="default-btn style-2 move-right">
    <span>I'm Button</span>
    </a>


          

Font size and Colors


You can Modify Font sizes and All colors of this template by channging the variable value in sass/sub-stylesheet/abstracts/variables.scss file


  $bootstrap-sass-asset-helper: false !default;
  //
  // Variables
  // --------------------------------------------------
  
  
  // Colors
  
  $title-color: #fff;
  $desc-color:#fff;
  $theme-color:#5138ee;
  //You can use these theme color options if you want or you can use your desire theme-color
  // $theme-color:#4ad0ee; //theme color optional theme-color
  // $theme-color:#d3ac5f; //theme color optional theme-color
  // $theme-color:#feda03; //theme color optional theme-color
  // $theme-color:#11d588; //theme color optional theme-color
  // $theme-color:#b2db5b; //theme color optional theme-color
  
  $theme-color-2:#ffd700;
  $primary-color: #3d8fff;
  $secondary-color:#1a203c;
  $body-color: #14192e;
  $body-color-2: #000d21;
  $royal-blue:#190955;
  $royal-yellow:#00edc5;
  $shadow-color: rgba($royal-blue, $alpha:.2);
  $white-color: #fff;
  $ash-color: #f9fafb;
  $black-color:#000000;
  $border-color: rgba($white-color, $alpha:.1);



  //=============== Typography
  
  // font-family
  
  $barlow:'Rajdhani',
  sans-serif;
  $roboto:'Roboto',
  sans-serif;
  
  // font-size
  
  $fs-base: 16px !default;
  $fs-small:14px;
  
  $fs-h1: 60px;
  $fs-h2: 40px;
  $fs-h3: 30px;
  $fs-h4: 24px;
  $fs-h5: 20px;
  $fs-h6: 18px;
          

Utility Classes
You can use all bootstrap's utility classes and besides this you also can you make your custom utility class in sass/sub-stylesheet/base/uitilities.scss file


  //--------------------------------------------
  //--This file contains all the utility classes
  //---------------------------------------------
  .theme-color {
  color: $theme-color;
  }
  
  .yellow-color {
  color: $royal-yellow;
  }
  
  .mb-30 {
  @extend %mb-30;
  }
  
  .gap-10 {
  gap: 10px;
  }
  
  .gap-15 {
  gap: 15px;
  }
  
  .fs-36 {
  @include font-size(36px);
  }
Change Copyright
You Can Change Your Copyright text by changing footer sections copyright part like below-

<div class="footer-bottom">
  <div class="container">
    <p class="text-center py-4 mb-0">All rights reserved &copy; EnftoMark || Design By: <a
    href="#">codexcoder</a>
    </p>
  </div>
</div>
    