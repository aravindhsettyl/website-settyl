<template>
  <div>
     <header class="container-fluid custom-fluid" style="    background: #202094;">
      <div class="container">
      <b-navbar toggleable="lg" type="light" variant="info">
    <a href="/">
    <img src="../assets/settyl.svg" alt="BoldSign" width="175" height="42">
    </a>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
         <b-nav-item-dropdown id="products-settyl" text="Products" right>
          <b-dropdown-item href="#"><span class="getting" style="
    display: flex;
    height: 56px;
    align-items: center;
    vertical-align: middle;
"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="ProductIcon ProductIcon--Billing "><title>Billing logo</title><path d="M26 2.46C26 1.1 24.9 0 23.53 0H2.47A2.47 2.47 0 0 0 0 2.46v30.08a2.46 2.46 0 0 0 3.47 2.25l10.2-4.53 10.86-4.83c.9-.4 1.47-1.27 1.47-2.25V2.46z" fill="url(#product-icon-billing-SiteMenu-a)"></path><path d="M26.5 39a13.5 13.5 0 1 0 0-27 13.5 13.5 0 0 0 0 27z" fill="#00D924"></path><path d="M26 12v11.18c0 .98-.57 1.86-1.47 2.25l-10.7 4.76A13.5 13.5 0 0 1 26 12z" fill="url(#product-icon-billing-SiteMenu-b)"></path><defs><linearGradient id="product-icon-billing-SiteMenu-a" x1="13" y1="6.35" x2="13" y2="35.03" gradientUnits="userSpaceOnUse"><stop stop-color="#FFD748"></stop><stop offset="1" stop-color="#FFC148"></stop></linearGradient><linearGradient id="product-icon-billing-SiteMenu-b" x1="19.5" y1="12.01" x2="19.5" y2="30.19" gradientUnits="userSpaceOnUse"><stop stop-color="#00A600"></stop><stop offset="1" stop-color="#00D924"></stop></linearGradient></defs></svg></span><span>Getting</span></span></b-dropdown-item>
          <b-dropdown-item href="#"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="ProductIcon ProductIcon--Billing "><title>Billing logo</title><path d="M26 2.46C26 1.1 24.9 0 23.53 0H2.47A2.47 2.47 0 0 0 0 2.46v30.08a2.46 2.46 0 0 0 3.47 2.25l10.2-4.53 10.86-4.83c.9-.4 1.47-1.27 1.47-2.25V2.46z" fill="url(#product-icon-billing-SiteMenu-a)"></path><path d="M26.5 39a13.5 13.5 0 1 0 0-27 13.5 13.5 0 0 0 0 27z" fill="#00D924"></path><path d="M26 12v11.18c0 .98-.57 1.86-1.47 2.25l-10.7 4.76A13.5 13.5 0 0 1 26 12z" fill="url(#product-icon-billing-SiteMenu-b)"></path><defs><linearGradient id="product-icon-billing-SiteMenu-a" x1="13" y1="6.35" x2="13" y2="35.03" gradientUnits="userSpaceOnUse"><stop stop-color="#FFD748"></stop><stop offset="1" stop-color="#FFC148"></stop></linearGradient><linearGradient id="product-icon-billing-SiteMenu-b" x1="19.5" y1="12.01" x2="19.5" y2="30.19" gradientUnits="userSpaceOnUse"><stop stop-color="#00A600"></stop><stop offset="1" stop-color="#00D924"></stop></linearGradient></defs></svg></span><span>Documentation</span></b-dropdown-item>
          <b-dropdown-item href="#"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="ProductIcon ProductIcon--Billing "><title>Billing logo</title><path d="M26 2.46C26 1.1 24.9 0 23.53 0H2.47A2.47 2.47 0 0 0 0 2.46v30.08a2.46 2.46 0 0 0 3.47 2.25l10.2-4.53 10.86-4.83c.9-.4 1.47-1.27 1.47-2.25V2.46z" fill="url(#product-icon-billing-SiteMenu-a)"></path><path d="M26.5 39a13.5 13.5 0 1 0 0-27 13.5 13.5 0 0 0 0 27z" fill="#00D924"></path><path d="M26 12v11.18c0 .98-.57 1.86-1.47 2.25l-10.7 4.76A13.5 13.5 0 0 1 26 12z" fill="url(#product-icon-billing-SiteMenu-b)"></path><defs><linearGradient id="product-icon-billing-SiteMenu-a" x1="13" y1="6.35" x2="13" y2="35.03" gradientUnits="userSpaceOnUse"><stop stop-color="#FFD748"></stop><stop offset="1" stop-color="#FFC148"></stop></linearGradient><linearGradient id="product-icon-billing-SiteMenu-b" x1="19.5" y1="12.01" x2="19.5" y2="30.19" gradientUnits="userSpaceOnUse"><stop stop-color="#00A600"></stop><stop offset="1" stop-color="#00D924"></stop></linearGradient></defs></svg></span><span>Features and Bugs</span></b-dropdown-item>
          <b-dropdown-item href="#"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="ProductIcon ProductIcon--Billing "><title>Billing logo</title><path d="M26 2.46C26 1.1 24.9 0 23.53 0H2.47A2.47 2.47 0 0 0 0 2.46v30.08a2.46 2.46 0 0 0 3.47 2.25l10.2-4.53 10.86-4.83c.9-.4 1.47-1.27 1.47-2.25V2.46z" fill="url(#product-icon-billing-SiteMenu-a)"></path><path d="M26.5 39a13.5 13.5 0 1 0 0-27 13.5 13.5 0 0 0 0 27z" fill="#00D924"></path><path d="M26 12v11.18c0 .98-.57 1.86-1.47 2.25l-10.7 4.76A13.5 13.5 0 0 1 26 12z" fill="url(#product-icon-billing-SiteMenu-b)"></path><defs><linearGradient id="product-icon-billing-SiteMenu-a" x1="13" y1="6.35" x2="13" y2="35.03" gradientUnits="userSpaceOnUse"><stop stop-color="#FFD748"></stop><stop offset="1" stop-color="#FFC148"></stop></linearGradient><linearGradient id="product-icon-billing-SiteMenu-b" x1="19.5" y1="12.01" x2="19.5" y2="30.19" gradientUnits="userSpaceOnUse"><stop stop-color="#00A600"></stop><stop offset="1" stop-color="#00D924"></stop></linearGradient></defs></svg></span><span>Release History</span></b-dropdown-item>
          <b-dropdown-item href="#"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="ProductIcon ProductIcon--Billing "><title>Billing logo</title><path d="M26 2.46C26 1.1 24.9 0 23.53 0H2.47A2.47 2.47 0 0 0 0 2.46v30.08a2.46 2.46 0 0 0 3.47 2.25l10.2-4.53 10.86-4.83c.9-.4 1.47-1.27 1.47-2.25V2.46z" fill="url(#product-icon-billing-SiteMenu-a)"></path><path d="M26.5 39a13.5 13.5 0 1 0 0-27 13.5 13.5 0 0 0 0 27z" fill="#00D924"></path><path d="M26 12v11.18c0 .98-.57 1.86-1.47 2.25l-10.7 4.76A13.5 13.5 0 0 1 26 12z" fill="url(#product-icon-billing-SiteMenu-b)"></path><defs><linearGradient id="product-icon-billing-SiteMenu-a" x1="13" y1="6.35" x2="13" y2="35.03" gradientUnits="userSpaceOnUse"><stop stop-color="#FFD748"></stop><stop offset="1" stop-color="#FFC148"></stop></linearGradient><linearGradient id="product-icon-billing-SiteMenu-b" x1="19.5" y1="12.01" x2="19.5" y2="30.19" gradientUnits="userSpaceOnUse"><stop stop-color="#00A600"></stop><stop offset="1" stop-color="#00D924"></stop></linearGradient></defs></svg></span><span>Resource Library</span></b-dropdown-item>
          <!-- <b-dropdown-item href="#">Other Products</b-dropdown-item> -->
        </b-nav-item-dropdown>
        <b-nav-item href="/about">Platforms</b-nav-item>
        <b-nav-item href="/about">Industries</b-nav-item>
        <b-nav-item-dropdown text="Resources" right>
          <b-dropdown-item href="#">Getting Started</b-dropdown-item>
          <b-dropdown-item href="#">Documentation</b-dropdown-item>
          <b-dropdown-item href="#">Features and Bugs</b-dropdown-item>
          <b-dropdown-item href="#">Release History</b-dropdown-item>
          <b-dropdown-item href="#">Video</b-dropdown-item>
          <b-dropdown-item href="#">Blog</b-dropdown-item>
          <b-dropdown-item href="#">Resource Library</b-dropdown-item>
          <b-dropdown-item href="#">Other Products</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown text="Company" right>
          <b-dropdown-item href="#">About</b-dropdown-item>
          <b-dropdown-item href="#">Customers</b-dropdown-item>
          <b-dropdown-item href="#">Press Releases</b-dropdown-item>
          <b-dropdown-item href="/contact">Contact US</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
          <!-- <b-nav-item href="#">Login</b-nav-item> -->
          <b-button size="sm" class="my-2 my-sm-0 custom-trial">Login</b-button>

        
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  </div>
    </header>

    <Nuxt />
    <footer style="padding-top: 60px;
    padding-bottom: 60px;
    margin-top: 0px;
    margin-bottom: 0px;    background: #0E0E64;">
      <div class="container">
        <div class="row">
          <div class="col-sm-5"><strong><a href="/" aria-current="page" class="active--exact active">
          <img alt="BoldSign" src="../assets/settyl.svg" width="175"  data-sizes="(max-width: 175px) 100vw, 175px" class="g-image g-image--lazy g-image--loaded" ></a></strong><div class="copyrights"><a href="">Copyright 2001-2021 Syncfusion Inc. <br>All Rights
              Reserved</a></div><div class="link"><a href="">Privacy Policy </a>
            |
            <a href="">Cookie Policy </a>
            |
            <a href="">Terms of Use </a></div></div>
            <div class="col-sm-2"><div class="head-1" style="color: #fff;">Quick Links</div><ul class="listings"><li><a href="">About us</a></li><li><a href="">Pricing &amp; FAQ</a></li><li><a href="">Documentation</a></li><li><a href="">Blog</a></li></ul></div><div class="col-sm-3"><div class="head-2" style="color: #fff;">Legal Stuff</div><ul class="listings"><li><a href="">About Disclaimer</a></li><li><a href="">Privacy Policy</a></li><li><a href="">Terms and Service</a></li></ul></div><div class="col-sm-2"><div class="head-3" style="color: #fff;">Follow Us</div><div class="social-groups"><a href="" class="fab fa-facebook"></a><a href="" class="fab fa-twitter"></a><a href="" class="fab fa-youtube"></a><a href="" class="fab fa-linkedin"></a></div></div></div>
        
      </div>
    </footer>

  </div>
</template>

<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-black.woff);

  font-weight: 900;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-heavy.woff);

  font-weight: 800;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-extra-bold.woff);

  font-weight: 700;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-bold.woff);

  font-weight: 600;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-medium.woff);

  font-weight: 500;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-light.woff);

  font-weight: 400;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-extra-light.woff);

  font-weight: 300;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros-thin.woff);

  font-weight: 200;
}

@font-face {
  font-family: Caros;

  src: url(../assets/font/Caros.woff);
}

* {
  font-family: Caros;
}


body {
  font-family: "Caros" !important;
  margin: 0;
  padding: 0;
  line-height: 1.5;
}


*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.layout {
  max-width: 1024px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.form-control:focus {
  border-color: #ced4da !important;
  box-shadow: none !important;
}

.btn-primary:focus {
  box-shadow: none !important;
}

.footer {
  margin-top: 100px;
  margin-bottom: 70px;
}

.head-1,
.head-2,
.head-3 {
  font-weight: 500;
  font-size: 18px;
  color: #141d30;
  margin-bottom: 12px;
}

/* .head-3 {
  margin-bottom: 22px;
} */

.listings {
  list-style-type: none;
  font-size: 16px;
  line-height: 2.5;
  padding: 0;
}

.listings li a:hover {
  color: #fe4901 !important;
  text-decoration: none;
}

.listings li a {
  color: #68758e !important;
}

.custom-input {
  height: 48px !important;
  font-size: 16px !important;
  line-height: 26px !important;
  border-radius: 6px 0 0 6px !important;
}

.join-button {
  padding: 0 32px !important;
  background: #fe4901 !important;
  border-color: #fe4901 !important;
}

.x-ruler {
  margin: 30px 0;
  color: #eeeeee;
}

.join-button:hover,
.custom-card-button:hover,
.card-button:hover,
.custom-trial:hover {
  background: #fe5b1a !important;
}

.join-button:active,
.custom-card-button:active,
.card-button:active,
.join-button:focus,
.custom-card-button:focus,
.card-button:focus {
  background: #fe9166 !important;
}

.social-groups {
  text-align: left;
}

.social-groups a {
  padding-right: 20px;
  font-size: 20px;
  color: #666e80;
}

.social-groups a:hover {
  text-decoration: none;
}

.copyrights {
  margin: 22px 0 12px 0;
}

.copyrights a {
  font-size: 14px;
  line-height: 24px;
  color: #68758e;
}

.copyrights a:hover {
  color: #fe4901;
  text-decoration: none;
}

/* .copyrights-content {
  font-size: 15px;
} */

.custom-trial {
  background-color: #00A9FA !important;
  border: none !important;
  color: rgb(255, 255, 255) !important;
  height: 42px;
  border-radius: 4px !important;
  padding: 0 20px !important;
  font-size: 16px !important;
  white-space: nowrap;
}

.custom-trial:focus {
  box-shadow: none !important;
}

.link a {
  font-size: 14px;
  line-height: 24px;
  color: #68758e;
}

.link a:hover {
  color: #fe4901;
  text-decoration: none;
}

.link {
  font-size: 14px;
  line-height: 24px;
  color: #68758e;
}

.custom-fluid {
  position: fixed;
  height: 86px;
  z-index: 3;
  background: #fff;
  background-color: rgba(255, 255, 255, 0.65);
  backdrop-filter: blur(10px);
  padding: 0 !important;
  top: 0;
}

.custom-fluid .bg-info {
  background-color: transparent !important;
  height: 86px;
}

.fa-facebook:hover {
  color: #1877f2;
}

.fa-twitter:hover {
  color: #1da1f2;
}

.fa-youtube:hover {
  color: #ff0000;
}

.fa-linkedin:hover {
  color: #2867b2;
}

.subscribe-mail {
  padding-top: 344px;
  
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
  position: relative;
}

.head-4 {
  color: #ffffff;
  font-size: 48px;
  font-weight: 700;
  line-height: 56px;
  padding-bottom: 40px;
}

.custom-subscription {
  margin-top: -260px;
}

.navbar-nav .nav-item .nav-link {
  color: #fff !important;
  font-size: 16px;
  font-weight: 500;
  line-height: 29px;
  padding-top: 7px;
  padding-bottom: 7px;
}

.navbar-nav .nav-item .nav-link:hover {
  color: #fe4901 !important;
}

.navbar-nav {
  margin-left: 100px;
}

@media (min-width: 992px) {
.navbar-expand-lg #nav-collapse .navbar-nav .nav-link {
  padding-right: 1.5rem;
  padding-left: 1.5rem;
}
}

.navbar-light .navbar-nav.ml-auto .nav-link {
  color: #fff !important;
  line-height: 29px;
  padding-top: 7px;
  padding-bottom: 7px;
}

.dropdown-toggle::after {
  margin-left: 6px !important;
  vertical-align: 3px !important;
  content: "";
  border: solid #fff !important;
  border-width: 0 1px 1px 0 !important;
  padding: 3px;
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}

.nav-link.dropdown-toggle:hover::after {
  border: solid #fe4901 !important;
  margin-left: 6px !important;
  vertical-align: 3px !important;
  content: "";
  border-width: 0 1px 1px 0 !important;
  padding: 3px;
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}

ul.dropdown-menu li {
  height: 44px;
  line-height: 36px;
}

.foot-input-group {
  max-width: 420px;
}

.custom-form-control,
.custom-form-control:focus {
  height: 56px !important;
  border-radius: 8px !important;
  max-width: 420px;
  border: 1px solid #fae3da;
  box-shadow: -2px 6px 16px 0 rgba(164, 148, 244, 0.25) !important;
  background: #ffffff;
  z-index: 0 !important;
  padding: 8px 8px 8px 16px !important;
}

.custom-secondary {
  height: 40px;
  margin-top: 8px;
  background: rgb(254, 73, 1) !important;
  border: none !important;
  color: rgb(255, 255, 255) !important;
  position: absolute;
  right: 10px;
  width: 160px;
  padding: 0 32px !important;
  z-index: 2 !important;
}

.custom-secondary:hover,
.custom-secondary:active {
  background: #fe5b1a !important;
}

.custom-secondary:focus {
  box-shadow: none !important;
}


#products-settyl ul.dropdown-menu.dropdown-menu-right.show {
    width: 620px;
        box-shadow: rgb(50 50 93 / 25%) 0px 50px 100px -20px, rgb(0 0 0 / 30%) 0px 30px 60px -30px;
}
#products-settyl ul.dropdown-menu li{
  display: inline-block;
  width: 49%;
}
#products-settyl .dropdown-menu-right {
    left: 0;
    right: auto;
}
.getting::before{
padding: 20px;
}
</style>
