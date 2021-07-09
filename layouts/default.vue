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
        <b-nav-item href="/platforms">Low code platform</b-nav-item>
         <b-nav-item-dropdown id="products-settyl" text="Products" right>
           <b-dropdown-item class="operation-menu-hover" href="/operational-planning"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
">
<img width="60" height="60" src="../assets/operational-prod.svg"  style="width:40px;"  class="fullimg" alt="" loading="lazy">
</span><span>Operational Planning</span></b-dropdown-item>
          <b-dropdown-item class="multi-menu-hover" href="/multi-modal-visibility"><span class="getting"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
">
<img width="60" height="60" src="../assets/multi-module.svg"  style="width:40px;"  class="fullimg" alt="" loading="lazy">
</span><span>Multimodal Visibility</span></span></b-dropdown-item>
          
          <b-dropdown-item class="risk-menu-hover" href="/risk-intelligence"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
">
<img width="60" height="60" src="../assets/risk-intelligence-prod.svg"  style="width:40px;"  class="fullimg" alt="" loading="lazy">
</span><span style="padding-right: 24px">Risk Intelligence & Customer Analytics</span></b-dropdown-item>
          <b-dropdown-item class="doc-menu-hover" href="#"><span style="
    width: 40px;
    height: 40px;
    margin-left: 12px;
        margin-right: 20px;
">
<img width="60" height="60" src="../assets/smart-doc-prod.svg"  style="width:40px;"  class="fullimg" alt="" loading="lazy">
</span><span>Smart Docs</span></b-dropdown-item>
          
          <!-- <b-dropdown-item href="#">Other Products</b-dropdown-item> -->
        </b-nav-item-dropdown>
        
        <b-nav-item href="/industries">Industries</b-nav-item>
        <b-nav-item-dropdown text="Resources" right>
          <b-dropdown-item href="https://appyoninfosolutions.com/settyl/blog/">Blog</b-dropdown-item>
          <b-dropdown-item href="#">Infographics</b-dropdown-item>
          <b-dropdown-item href="#">Case Studies</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown text="Company" right>
          <b-dropdown-item href="/about">About Us</b-dropdown-item>
          <b-dropdown-item href="/contact">Contact Us</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
          <!-- <b-nav-item href="#">Login</b-nav-item> -->
          <b-button size="sm" class="my-2 my-sm-0 custom-trial outline" style="width: 92px !important; background: none !important;border: 1px solid #fff !important; margin-right: 12px !important;">Login</b-button>
          <b-button size="sm" class="my-2 my-sm-0 custom-trial" v-b-modal.modal-1>Book Demo</b-button>
<!-- <b-button v-b-modal.modal-1 class="custom-trial">Get a demo</b-button> -->
        
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
          <div class="col-sm-4"><strong><a href="/" aria-current="page" class="active--exact active">
          <img alt="BoldSign" src="../assets/settyl.svg" width="175"  data-sizes="(max-width: 175px) 100vw, 175px" class="g-image g-image--lazy g-image--loaded" ></a></strong>
          <div class="copyrights"><a href="" style="color: #A2A2E3 !important;">Ph: +1 6478198103</a><br/>
          <a href="" style="color: #A2A2E3 !important;">contact@settyl.com</a>
          </div>
          <div class="social-groups">
              <a href="" class="fab fa-facebook-icon"></a>
              <a href="" class="fab fa-twitter-icon"></a>
              <a href="" class="fab fa-youtube-icon"></a>
              <a href="" class="fab fa-linkedin-icon"></a>
            </div>

          <!-- <div class="link"><a href="">Privacy Policy </a>
            |
            <a href="">Cookie Policy </a>
            |
            <a href="">Terms of Use </a></div> -->
            </div>
            <div class="col-sm-3"><div class="head-1" style="color: #fff;">Company</div>
            <ul class="listings">
              <li><a href="">About us</a></li>
              <li><a href="">Become a partner</a></li>
              <li><a href="">Join our Affiliate Program</a></li>
              <li><a href="">Sales</a></li>
              <li><a href="">Support</a></li>
              <li><a href="">Press Release</a></li>
            </ul>
            </div>
            <div class="col-sm-3"><div class="head-2" style="color: #fff;">Legal Stuff</div>
            <ul class="listings">
              <li><a href="">Real Time Tracking</a></li>
              <li><a href="">Smart Route Forecast</a></li>
              <li><a href="">Supply Chain Risks</a></li>
              <li><a href="">Delivery Orchestration</a></li>
              <li><a href="">Purchase Order Visibility</a></li>
              <li><a href="">Paperless Docs</a></li>
              <li><a href="">Autonomous Dispatch</a></li>
            </ul>
            </div>
            <div class="col-sm-2"><div class="head-3" style="color: #fff;">Case studies</div>
            <ul class="listings">
              <li><a href="">Shippers</a></li>
              <li><a href="">Carriers/3PLs</a></li>
            </ul>
            </div>
        </div>
      </div>
      <div id="copyrightWrapper" class="container grid-x grid-margin-x align-middle">
            <!--Column--->
            <div class="cell" style="    text-align: left;
    margin-top: 32px;
    color: rgb(162, 162, 227) !important;
    border-top: 1px solid #23237e;
    padding-top: 24px;">
                    © 2021 Settyl Inc. All rights reserved&nbsp;&nbsp;|&nbsp;&nbsp;<a href="/privacy-policy/" title="Privacy Policy" style="    color: rgb(162, 162, 227) !important;">Privacy Policy</a>&nbsp;&nbsp;|&nbsp;&nbsp;<a href="/terms-of-service/" title="Terms of Service" style="    color: rgb(162, 162, 227) !important;">Terms of Service</a>
            </div>
            <!--/end Column--->
        </div>
    </footer>
 <b-modal id="modal-1" title="" hide-footer style="max-width: 650px;">
    <div class="card-body contact-card-body" style="    padding-left: 40px;
    padding-right: 40px;">
                <h5 class="card-title contact-card-title" style="text-align:center;
                
font-size: 28px;
color: #171E35;
letter-spacing: 0;
text-align: center;">Book a Demo</h5>
                <p style="    margin: 0px auto;
    text-align: center;    padding-bottom: 24px; font-size: 16px;
color: #4E5874;
letter-spacing: 0;
text-align: center;
line-height: 26px;">Please fill in the form below.<br/>
We will get back to you within 24 hours. </p>
                 <form ref="form" @submit.stop.prevent="handleSubmit">
                   <div style="    display: inline-flex;
    width: 100%;">
        <b-form-group
          label="Firstname *"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          style="width: 50%;padding-right: 32px;"
        >
          <b-form-input
            id="name-input"
            v-model="Firstname"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
        <b-form-group
          label="Lastname"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          style="width: 50%"
        >
          <b-form-input
            id="name-input"
            v-model="name"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
        </div>
        <b-form-group
          label="Business Email *"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          
        >
          <b-form-input
            id="name-input"
            v-model="name"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
        <b-form-group
          label="Company Name"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          
        >
          <b-form-input
            id="name-input"
            v-model="name"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
        <b-form-group
          label="Phone Number"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          
        >
          <b-form-input
            id="name-input"
            v-model="name"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
        <b-form-group
          label="Country *"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          
        >
          <b-form-input
            id="name-input"
            v-model="name"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
        <b-form-group
          label="What Type Solution are you looking For?"
          label-for="name-input"
          invalid-feedback="Name is required"
          :state="nameState"
          
        >
          <b-form-input
            id="name-input"
            v-model="name"
            :state="nameState"
            required
          ></b-form-input>
        </b-form-group>
      </form>
                <!-- <div class="input-group mb-3">
                <input
                  type="text"
                  class="form-control contact-input"
                  placeholder="Name"
                  aria-label="Name"
                  aria-describedby="basic-addon2"
                  v-model="userName"
                />
              </div>
              <div class="input-group mb-3">
                <input
                  type="text"
                  class="form-control contact-input"
                  placeholder="Email"
                  aria-label="Email"
                  aria-describedby="basic-addon2"
                  v-model="email"
                />
              </div>
              <div class="input-group mb-3">
                <input
                  type="text"
                  class="form-control contact-input"
                  placeholder="Company"
                  aria-label="Company"
                  aria-describedby="basic-addon2"
                  v-model="company"
                />
              </div>
              <div class="input-group mb-3">
                <input
                  type="text"
                  class="form-control contact-input"
                  placeholder="Phone"
                  aria-label="Phone"
                  aria-describedby="basic-addon2"
                  v-model="phoneNumber"
                />
              </div>
              <div class="input-group mb-3">
                <textarea
                  type="text"
                  class="form-control contact-multi-line"
                  placeholder="Message"
                  aria-label="Message"
                  aria-describedby="basic-addon2"
                  v-model="message"
                />
              </div> -->
                
                <div class="secure">Settyl uses the information you submit to contact you via email or phone. You may unsubscribe at any time. See our <a href="/terms-of-use/">Privacy Policy </a> or <a href="/contact/"> Contact us</a> for more information</div>
                <div v-if="isFormSubmitted" class="success_msg">Form is submitted successfully.</div>
                <a class="btn btn-primary custom-contact-btn" style="width: 100%; margin-top: 12px;background-color: #3E3CDA;margin-bottom: 24px;border: none" v-bind:class="isAgreeCheck ? '' : ''">Submit Request</a>
              </div>

  </b-modal>
  </div>
</template>
<style>

#modal-1 .modal-dialog{
  max-width: 650px !important;
}
#modal-1 div#modal-1___BV_modal_body_{
  padding-top: 0px;
}

#modal-1 .modal-header{
  padding-bottom: 0px;
  border: none;
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
.dropdown-menu.show {
    display: block;
    /* height: 316px; */
    border-radius: 5px !important;
    box-shadow: 0px 0px 20px 0px rgba(0,0,0,.1) !important;
    border: none;
    right: auto;
    left: 0;
    padding: 16px;
    border-radius: 12px !important;
}
#products-settyl ul.dropdown-menu {
    height: 316px;
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

.fa, .fab, .fad, .fal, .far, .fas {
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    display: inline-block;
    font-style: normal;
    font-variant: normal;
    text-rendering: auto;
    line-height: 1;
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
  color: #fff !important;
  text-decoration: none;
}

.listings li a {
  color: #fff !important;
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
  background: #028ed2 !important;
}

.join-button:active,
.custom-card-button:active,
.card-button:active,
.join-button:focus,
.custom-card-button:focus,
.card-button:focus {
  background: #028ed2 !important;
}

.social-groups {
  text-align: left;
}

.social-groups a {
  margin-right: 20px;
  font-size: 20px;
  width: 20px;
  height: 20px;
  color: #666e80;
}

.social-groups .fab {
  background-image: url(../assets/social-icon.png);
  background-size: 50px;
}

.fa-facebook-icon {
  background-position: -4px -3px;
}
.fa-twitter-icon {
  background-position: -4px -41px;
}
.fa-youtube-icon{
  background-position: -4px -23px;
}
.fa-linkedin-icon{
  background-position: -4px -63px;
}

.fa-facebook-icon:hover {
  background-position: -27px -3px;
}
.fa-twitter-icon:hover {
  background-position: -27px -41px;
}
.fa-youtube-icon:hover {
  background-position: -27px -23px;
}
.fa-linkedin-icon:hover {
  background-position: -27px -63px;
}

.social-groups a:hover {
  text-decoration: none;
}

.copyrights {
  margin: 22px 0 12px 0;
}

.copyrights div {
  font-size: 14px;
  line-height: 24px;
  color: #68758e;
}

.custom-trial {
      background: #00A9FA;
  border: none !important;
  color: rgb(255, 255, 255) !important;
  height: 42px;
  border-radius: 4px !important;
  padding: 0 20px !important;
  font-size: 16px !important;
  white-space: nowrap;
  line-height: 42px !important;
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
  z-index: 3;
  background: #fff;
  background-color: rgba(255, 255, 255, 0.80);
  backdrop-filter: blur(10px);
  padding: 0 !important;
  top: 0;
}

@-moz-document url-prefix(){
  .custom-fluid {
  background-color: rgba(255, 255, 255, 0.95);
}
}

.custom-fluid .bg-info {
  background-color: transparent !important;
  padding: 16px 0px;
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
  padding: 48px 56px;
  /* background-image: url(../assets/images/footer-bg.jpg); */
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

.navbar-nav .nav-item .nav-link {
  color: #fff !important;
  font-size: 16px;
  font-weight: 500;
  line-height: 29px;
  padding-top: 7px;
  padding-bottom: 7px;
}

.navbar-nav .nav-item .nav-link:hover {
  color: #fff !important;
}

.navbar-nav {
  margin-left: 56px;
}
.navbar-collapse.collapse.show {
    height: calc(100vh - 92px);
    overflow: auto;
}
@media (min-width: 992px) {
.navbar-expand-lg #nav-collapse .navbar-nav .nav-link {
  padding-right: 1rem;
  padding-left: 1rem;
}
}

.navbar-light .navbar-nav.ml-auto .nav-link {
  color: #FE4901 !important;
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

.custom-button-container {
    text-align: center;
    display: none;
}
.custom-secondary-responsive {
    height: 40px !important;
    margin-top: 8px !important;
    background: #fe4901 !important;
    border: none !important;
    color: white !important;
    width: 170px !important;
    padding: 0 26px !important;
    outline: none !important;
    box-shadow: none !important;
}

.custom-secondary:hover,
.custom-secondary:active,
.custom-secondary-responsive:hover,
.custom-secondary-responsive:active {
  background: #d63f04 !important;
  box-shadow: none !important;
}

.nav-link.dropdown-toggle:hover::after {
  border: solid #fff !important;
  margin-left: 6px !important;
  vertical-align: 3px !important;
  content: "";
  border-width: 0 1px 1px 0 !important;
  padding: 3px;
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}

ul.dropdown-menu li {
  height: 68px;
  line-height: 68px;
}

.custom-form-control,
.custom-form-control:focus {
  height: 56px !important;
  border-radius: 8px !important;
  max-width: 540px;
  border: 1px solid #fae3da;
  box-shadow: -2px 6px 16px 0 rgba(164, 148, 244, 0.25) !important;
  background: #ffffff;
  z-index: 0 !important;
  padding: 8px 196px 8px 16px !important;
}

.custom-secondary {
  height: 40px;
  margin-top: 8px;
  background: rgb(254, 73, 1) !important;
  border: none !important;
  color: rgb(255, 255, 255) !important;
  position: absolute;
  width: 170px;
  right: 10px;
  padding: 0 26px !important;
  z-index: 2 !important;
}
#products-settyl .dropdown-item{
    padding: 0.25rem 0.25rem !important;
}

.dropdown-item.active, .dropdown-item:active {
   color: #333 !important;
    text-decoration: none !important;
    background-color: #ffede5 !important;
}

.custom-subscription {
  text-align: center;
}

.row.custom-row {
  display: none;
}

.navbar-toggler-icon {
  width: 20px !important;
  height: 20px !important;
}

@media only screen and (max-width: 1024px) {
  .custom-footer-row-1 {
    flex: 0 0 50% !important;
    max-width: 50% !important;
  }

  .custom-footer-row-2 {
    flex: 0 0 25% !important;
    max-width: 25% !important;
  }

  .custom-footer-row-3 {
    display: none;
  }

  .row.custom-row {
    display: flex;
    padding-top: 20px;
  }

  .heading-1 {
    font-size: 48px !important;
    line-height: 56px !important;
  }

  .content-1 {
    font-size: 18px !important;
    line-height: 28px !important;
  }

  .all-features {
    margin-top: 30px !important;
  }

  .input-block {
    margin-top: 40px !important;
  }

  .head-4 {
    font-size: 28px !important;
    padding-bottom: 30px;
  }

  .subscribe-mail {
    padding: 40px 15px;
  }


  #nav-collapse .navbar-nav {
    margin-left: 26px;
  }
}

@media only screen and (max-width: 768px) {
  .custom-button-container {
    display: block !important;
  }
  .custom-secondary {
    display: none !important;
  }
  .custom-footer-row-2 {
    display: none;
  }

  .custom-footer-row-4 {
    display: none;
  }

  .custom-footer-row-1 {
    flex: 0 0 100% !important;
    max-width: 100% !important;
    text-align: center;
  }

  .custom-null {
    display: none;
  }

  .custom-follow-us {
    flex: 0 0 100% !important;
    max-width: 100% !important;
    text-align: center;
  }

  .social-groups {
    text-align: center;
  }

  .row.custom-row {
    padding-top: 60px;
  }

  .heading-1 {
    font-size: 48px !important;
    line-height: 54px !important;
  }

  .content-1 {
    font-size: 16px !important;
    line-height: 26px !important;
  }

  .all-features {
    font-size: 14px;
  }

  .heading-4, .heading-3, .heading-5, .heading-6, .heading-7, .heading-8, .heading-9 {
    font-size: 28px !important;
    line-height: 36px !important;
  }

  .content-4, .content-3, .content-5, .content-6, .content-7, .content-8, .content-9 {
    font-size: 14px !important;
    line-height: 24px !important;
  }

  .compare-head-price {
    font-size: 18px !important;
    line-height: 29px !important;
  }

  .head-4 {
    font-size: 28px !important;
    padding-bottom: 20px !important;
    line-height: 36px;
  }

 
}


@media only screen and (max-width: 991px) and (min-width: 768px) {
.custom-fluid{
    background-color: rgb(255 255 255);
    backdrop-filter: blur(0px);
}
.navbar-nav .nav-item {
    padding: 7px 0px;
    border-bottom: 1px solid #d3e2ed;
}
#nav-collapse .navbar-nav{
  margin-top: 16px;
      margin-left: 16px;
}
.navbar-light .navbar-nav.ml-auto .nav-link{
  text-align: center;
}
.navbar-nav .nav-item .nav-link span {
    display: inline-block;
    width: calc(100% - 32px);
}
.dropdown-menu.show{
  box-shadow: none !important;
}
.navbar-light .navbar-toggler{
  border: none;
}
.navbar-light .navbar-toggler-icon{
  background-image:url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM4NHB0IiB2aWV3Qm94PSIwIC01MyAzODQgMzg0IiB3aWR0aD0iMzg0cHQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0ibTM2OCAxNTQuNjY3OTY5aC0zNTJjLTguODMyMDMxIDAtMTYtNy4xNjc5NjktMTYtMTZzNy4xNjc5NjktMTYgMTYtMTZoMzUyYzguODMyMDMxIDAgMTYgNy4xNjc5NjkgMTYgMTZzLTcuMTY3OTY5IDE2LTE2IDE2em0wIDAiLz48cGF0aCBkPSJtMzY4IDMyaC0zNTJjLTguODMyMDMxIDAtMTYtNy4xNjc5NjktMTYtMTZzNy4xNjc5NjktMTYgMTYtMTZoMzUyYzguODMyMDMxIDAgMTYgNy4xNjc5NjkgMTYgMTZzLTcuMTY3OTY5IDE2LTE2IDE2em0wIDAiLz48cGF0aCBkPSJtMzY4IDI3Ny4zMzIwMzFoLTM1MmMtOC44MzIwMzEgMC0xNi03LjE2Nzk2OS0xNi0xNnM3LjE2Nzk2OS0xNiAxNi0xNmgzNTJjOC44MzIwMzEgMCAxNiA3LjE2Nzk2OSAxNiAxNnMtNy4xNjc5NjkgMTYtMTYgMTZ6bTAgMCIvPjwvc3ZnPg==") !important;
}
.navbar-light .not-collapsed .navbar-toggler-icon{
  background-image:url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjMxMXB0IiB2aWV3Qm94PSIwIDAgMzExIDMxMS4wNzczMyIgd2lkdGg9IjMxMXB0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Im0xNi4wMzUxNTYgMzExLjA3ODEyNWMtNC4wOTc2NTYgMC04LjE5NTMxMi0xLjU1ODU5NC0xMS4zMDg1OTQtNC42OTUzMTMtNi4yNS02LjI1LTYuMjUtMTYuMzgyODEyIDAtMjIuNjMyODEybDI3OS4wNjI1LTI3OS4wNjI1YzYuMjUtNi4yNSAxNi4zODI4MTMtNi4yNSAyMi42MzI4MTMgMHM2LjI1IDE2LjM4MjgxMiAwIDIyLjYzNjcxOWwtMjc5LjA1ODU5NCAyNzkuMDU4NTkzYy0zLjEzNjcxOSAzLjExNzE4OC03LjIzNDM3NSA0LjY5NTMxMy0xMS4zMjgxMjUgNC42OTUzMTN6bTAgMCIvPjxwYXRoIGQ9Im0yOTUuMTE3MTg4IDMxMS4wNzgxMjVjLTQuMDk3NjU3IDAtOC4xOTE0MDctMS41NTg1OTQtMTEuMzA4NTk0LTQuNjk1MzEzbC0yNzkuMDgyMDMyLTI3OS4wNTg1OTNjLTYuMjUtNi4yNTM5MDctNi4yNS0xNi4zODY3MTkgMC0yMi42MzY3MTlzMTYuMzgyODEzLTYuMjUgMjIuNjM2NzE5IDBsMjc5LjA1ODU5NCAyNzkuMDYyNWM2LjI1IDYuMjUgNi4yNSAxNi4zODI4MTIgMCAyMi42MzI4MTItMy4xMzY3MTkgMy4xMTcxODgtNy4yMzA0NjkgNC42OTUzMTMtMTEuMzA0Njg3IDQuNjk1MzEzem0wIDAiLz48L3N2Zz4=") !important;
}
 .homepage-header {
    padding-top: 120px !important;
  }
}

@media only screen and (max-width: 767px) and (min-width: 320px) {
.custom-fluid{
    background-color: rgb(255 255 255);
    backdrop-filter: blur(0px);
}
.navbar-nav .nav-item {
    padding: 7px 0px;
    border-bottom: 1px solid #d3e2ed;
}
#nav-collapse .navbar-nav{
  margin-top: 16px;
  margin-left: 8px;
}
.navbar-light .navbar-nav.ml-auto .nav-link{
  text-align: center;
}
.navbar-nav .nav-item .nav-link span {
    display: inline-block;
    width: calc(100% - 32px);
}
.dropdown-menu.show{
  box-shadow: none !important;
}
.navbar-light .navbar-toggler{
  border: none;
}
.navbar-light .navbar-toggler-icon{
  background-image:url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM4NHB0IiB2aWV3Qm94PSIwIC01MyAzODQgMzg0IiB3aWR0aD0iMzg0cHQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0ibTM2OCAxNTQuNjY3OTY5aC0zNTJjLTguODMyMDMxIDAtMTYtNy4xNjc5NjktMTYtMTZzNy4xNjc5NjktMTYgMTYtMTZoMzUyYzguODMyMDMxIDAgMTYgNy4xNjc5NjkgMTYgMTZzLTcuMTY3OTY5IDE2LTE2IDE2em0wIDAiLz48cGF0aCBkPSJtMzY4IDMyaC0zNTJjLTguODMyMDMxIDAtMTYtNy4xNjc5NjktMTYtMTZzNy4xNjc5NjktMTYgMTYtMTZoMzUyYzguODMyMDMxIDAgMTYgNy4xNjc5NjkgMTYgMTZzLTcuMTY3OTY5IDE2LTE2IDE2em0wIDAiLz48cGF0aCBkPSJtMzY4IDI3Ny4zMzIwMzFoLTM1MmMtOC44MzIwMzEgMC0xNi03LjE2Nzk2OS0xNi0xNnM3LjE2Nzk2OS0xNiAxNi0xNmgzNTJjOC44MzIwMzEgMCAxNiA3LjE2Nzk2OSAxNiAxNnMtNy4xNjc5NjkgMTYtMTYgMTZ6bTAgMCIvPjwvc3ZnPg==") !important;
}
.navbar-light .not-collapsed .navbar-toggler-icon{
  background-image:url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjMxMXB0IiB2aWV3Qm94PSIwIDAgMzExIDMxMS4wNzczMyIgd2lkdGg9IjMxMXB0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Im0xNi4wMzUxNTYgMzExLjA3ODEyNWMtNC4wOTc2NTYgMC04LjE5NTMxMi0xLjU1ODU5NC0xMS4zMDg1OTQtNC42OTUzMTMtNi4yNS02LjI1LTYuMjUtMTYuMzgyODEyIDAtMjIuNjMyODEybDI3OS4wNjI1LTI3OS4wNjI1YzYuMjUtNi4yNSAxNi4zODI4MTMtNi4yNSAyMi42MzI4MTMgMHM2LjI1IDE2LjM4MjgxMiAwIDIyLjYzNjcxOWwtMjc5LjA1ODU5NCAyNzkuMDU4NTkzYy0zLjEzNjcxOSAzLjExNzE4OC03LjIzNDM3NSA0LjY5NTMxMy0xMS4zMjgxMjUgNC42OTUzMTN6bTAgMCIvPjxwYXRoIGQ9Im0yOTUuMTE3MTg4IDMxMS4wNzgxMjVjLTQuMDk3NjU3IDAtOC4xOTE0MDctMS41NTg1OTQtMTEuMzA4NTk0LTQuNjk1MzEzbC0yNzkuMDgyMDMyLTI3OS4wNTg1OTNjLTYuMjUtNi4yNTM5MDctNi4yNS0xNi4zODY3MTkgMC0yMi42MzY3MTlzMTYuMzgyODEzLTYuMjUgMjIuNjM2NzE5IDBsMjc5LjA1ODU5NCAyNzkuMDYyNWM2LjI1IDYuMjUgNi4yNSAxNi4zODI4MTIgMCAyMi42MzI4MTItMy4xMzY3MTkgMy4xMTcxODgtNy4yMzA0NjkgNC42OTUzMTMtMTEuMzA0Njg3IDQuNjk1MzEzem0wIDAiLz48L3N2Zz4=") !important;
}
 .homepage-header {
    padding-top: 120px !important;
  }
}

@media only screen and (max-width: 768px) {
.custom-form-control, .custom-form-control:focus {
  height: 44px !important;
  padding: 8px 16px 8px 16px !important;
}
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
  color: #fff !important;
  text-decoration: none;
}

.listings li a {
  color: rgb(162, 162, 227)  !important;
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
  background: #00A9FA !important;
}

.join-button:active,
.custom-card-button:active,
.card-button:active,
.join-button:focus,
.custom-card-button:focus,
.card-button:focus {
  background: #00A9FA !important;
}

.social-groups {
  text-align: left;
}

.social-groups a {
  margin-right: 20px;
  font-size: 20px;
  width: 20px;
  height: 20px;
  color: #666e80;
}

.social-groups .fab {
  /* background-image: url(../assets/images/social-icons.png); */
  background-size: 50px;
}

.fa-facebook-icon {
  background-position: -4px -3px;
}
.fa-twitter-icon {
  background-position: -4px -41px;
}
.fa-youtube-icon{
  background-position: -4px -23px;
}
.fa-linkedin-icon{
  background-position: -4px -63px;
}

.fa-facebook-icon:hover {
  background-position: -27px -3px;
}
.fa-twitter-icon:hover {
  background-position: -27px -41px;
}
.fa-youtube-icon:hover {
  background-position: -27px -23px;
}
.fa-linkedin-icon:hover {
  background-position: -27px -63px;
}

.social-groups a:hover {
  text-decoration: none;
}

.copyrights {
  margin: 22px 0 12px 0;
}

.copyrights div {
  font-size: 14px;
  line-height: 24px;
  color: #68758e;
}

.custom-trial {
  background-color: #00A9FA !important;
  border: none !important;
  color: rgb(255, 255, 255) !important;
  height: 42px;
  border-radius: 4px !important;
  padding: 0 20px !important;
  font-size: 16px !important;
  white-space: nowrap;
  line-height: 42px !important;
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
  color: #00A9FA;
  text-decoration: none;
}

.link {
  font-size: 14px;
  line-height: 24px;
  color: #68758e;
}

.custom-fluid {
  position: fixed;
  z-index: 3;
  background: #fff;
  background-color: rgba(255, 255, 255, 0.80);
  backdrop-filter: blur(10px);
  padding: 0 !important;
  top: 0;
}

#cookie {
    width: 100%;
    bottom: 0;
    position: fixed;
    background-color: #0f0f0f;
    opacity: .9;
    z-index: 10;
    padding: 20px 0;
    display: block;
    text-align: center;
    animation: slidebottom .5s;
    left: 0;
}

#cookie #custom-popup-text {
    color: #fff;
    line-height: 28px;
    letter-spacing: .5px;
    display: inline-block;
    font-size: 14px;
    font-weight: 400;
}

#cookie #custom-popup-text a {
    color: #fd0;
}

#cookie .custom-agree-button {
    letter-spacing: .5px;
    padding: 8px 0;
    text-align: center;
    font-family: 'Caros',sans-serif;
    font-weight: 500;
    background-color: #ff4800;
    color: #fff;
    border-radius: 2px !important;
    width: 120px;
    cursor: pointer;
    margin-left: 30px;
    display: inline-block;
}
#cookie .custom-agree-button:hover{
  background: #fff;
  color: #ff4800;
}

@keyframes slidebottom{
  0% {
      bottom: -300px;
      opacity: 0;
  }

  100% {
      bottom: 0;
      opacity: 1;
  }
}

@media (max-width: 767px){
#cookie #custom-popup-text {
    padding: 0 15px;
    line-height: 25px;
    width: 100%;
}
#cookie .custom-agree-button {
    vertical-align: unset;
    margin: 15px 0 0;
}
}

@media(min-width: 1025px) {
  .bs-bodychat #liveChatApp #chatIcon {
    bottom: 101px;
  }
  .bs-bodychat #liveChatApp #chatOption {
    bottom: 70px;
  }
  .bs-bodychat #liveChatApp #livechat {
    bottom: 95px;
  }
}

@media (max-width: 1279px) and (min-width: 768px){
#cookie #custom-popup-text {
    width: 75%;
}
#cookie .custom-agree-button {
    vertical-align: text-bottom;
}
}

@media (max-width: 1024px) and (min-width: 768px){
#cookie #custom-popup-text {
     padding: 0 15%;
    line-height: 25px;
    width: 100%;
}
#cookie .custom-agree-button {
    vertical-align: unset;
    margin: 15px 0 0;
}
}

@media (max-width: 992px) and (min-width: 768px){
#cookie #custom-popup-text {
     padding: 0 8%;
}
}
@-moz-document url-prefix(){
  .custom-fluid {
    background-color: rgba(255, 255, 255, 0.95);
  }
}

.custom-fluid .bg-info {
  background-color: transparent !important;
  padding: 16px 0px;
}

.subscribe-mail {
  padding: 48px 56px;
  background-image: linear-gradient( 173deg, #2566F0 20%, #5E0C84 100%);
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

.navbar-nav .nav-item .nav-link {
  color: rgb(255 255 255 / 90%) !important;
    font-size: 14px;
    font-weight: 400;
    line-height: 29px;
    letter-spacing: 0.2px;
    padding-top: 7px;
    padding-bottom: 7px;
}

.navbar-nav .nav-item .nav-link:hover {
  color: #fff !important;
}

.navbar-nav {
  margin-left: 56px;
}
.navbar-collapse.collapse.show {
    height: calc(100vh - 92px);
    overflow: auto;
}
@media (min-width: 992px) {
.navbar-expand-lg #nav-collapse .navbar-nav .nav-link {
  padding-right: 1rem;
  padding-left: 1rem;
}
}

.navbar-light .navbar-nav.ml-auto .nav-link {
  color: #FE4901 !important;
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

.custom-button-container {
    text-align: center;
    display: none;
}
.custom-secondary-responsive {
    height: 40px !important;
    margin-top: 8px !important;
    background: #fe4901 !important;
    border: none !important;
    color: white !important;
    width: 170px !important;
    padding: 0 26px !important;
    outline: none !important;
    box-shadow: none !important;
}

.custom-secondary:hover,
.custom-secondary:active,
.custom-secondary-responsive:hover,
.custom-secondary-responsive:active {
  background: #fff !important;
  box-shadow: none !important;
}

.nav-link.dropdown-toggle:hover::after {
  border: solid #fff !important;
  margin-left: 6px !important;
  vertical-align: 3px !important;
  content: "";
  border-width: 0 1px 1px 0 !important;
  padding: 3px;
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}
li.multi-menu-hover a:hover, li.multi-menu-hover a:active{
  background: #FFF2F7 !important;
  border-radius: 4px;
}
li.operation-menu-hover a:hover, li.operation-menu-hover a:active{
  background: #E7FAF0 !important;
  border-radius: 4px;
}
li.risk-menu-hover a:hover, li.risk-menu-hover a:active{
  background: #E5FAF9 !important;
  border-radius: 4px;
}
li.doc-menu-hover a:hover, li.doc-menu-hover a:active{
  background: #E9F8FE !important;
  border-radius: 4px;
}
ul.dropdown-menu li {
  height: 68px;
  line-height: 68px;
}

.custom-form-control,
.custom-form-control:focus {
  height: 56px !important;
  border-radius: 8px !important;
  max-width: 540px;
  border: 1px solid #fae3da;
  box-shadow: -2px 6px 16px 0 rgba(164, 148, 244, 0.25) !important;
  background: #ffffff;
  z-index: 0 !important;
  padding: 8px 196px 8px 16px !important;
}

.custom-secondary {
  height: 40px;
  margin-top: 8px;
  background: rgb(254, 73, 1) !important;
  border: none !important;
  color: rgb(255, 255, 255) !important;
  position: absolute;
  width: 170px;
  right: 10px;
  padding: 0 26px !important;
  z-index: 2 !important;
}
.dropdown-item.active, .dropdown-item:active {
   color: #333 !important;
    text-decoration: none !important;
    background-color: #ffede5 !important;
}

.custom-subscription {
  text-align: center;
}

.row.custom-row {
  display: none;
}

.navbar-toggler-icon {
  width: 20px !important;
  height: 20px !important;
}

@media only screen and (max-width: 1024px) {
  .custom-footer-row-1 {
    flex: 0 0 50% !important;
    max-width: 50% !important;
  }

  .custom-footer-row-2 {
    flex: 0 0 25% !important;
    max-width: 25% !important;
  }

  .custom-footer-row-3 {
    display: none;
  }

  .row.custom-row {
    display: flex;
    padding-top: 20px;
  }

  .heading-1 {
    font-size: 48px !important;
    line-height: 56px !important;
  }

  .content-1 {
    font-size: 18px !important;
    line-height: 28px !important;
  }

  .all-features {
    margin-top: 30px !important;
  }

  .input-block {
    margin-top: 40px !important;
  }

  .head-4 {
    font-size: 28px !important;
    padding-bottom: 30px;
  }

  .subscribe-mail {
    padding: 40px 15px;
  }

  #nav-collapse .navbar-nav {
    margin-left: 26px;
  }
}

@media only screen and (max-width: 991px) {
  .custom-fluid {
    background-color: rgb(255 255 255);
    backdrop-filter: blur(0px);
  }
  .navbar-nav .nav-item {
    padding: 7px 0px;
    border-bottom: 1px solid #d3e2ed;
  }
  .navbar-light .navbar-nav.ml-auto .nav-link{
    text-align: center;
  }
  .navbar-nav .nav-item .nav-link span {
    display: inline-block;
    width: calc(100% - 32px);
  }
  .dropdown-menu.show{
    box-shadow: none !important;
  }
  .navbar-light .navbar-toggler{
    border: none;
  }
  .homepage-header {
    padding-top: 120px !important;
  }
  .navbar-light .navbar-toggler-icon {
    background-image:url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM4NHB0IiB2aWV3Qm94PSIwIC01MyAzODQgMzg0IiB3aWR0aD0iMzg0cHQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0ibTM2OCAxNTQuNjY3OTY5aC0zNTJjLTguODMyMDMxIDAtMTYtNy4xNjc5NjktMTYtMTZzNy4xNjc5NjktMTYgMTYtMTZoMzUyYzguODMyMDMxIDAgMTYgNy4xNjc5NjkgMTYgMTZzLTcuMTY3OTY5IDE2LTE2IDE2em0wIDAiLz48cGF0aCBkPSJtMzY4IDMyaC0zNTJjLTguODMyMDMxIDAtMTYtNy4xNjc5NjktMTYtMTZzNy4xNjc5NjktMTYgMTYtMTZoMzUyYzguODMyMDMxIDAgMTYgNy4xNjc5NjkgMTYgMTZzLTcuMTY3OTY5IDE2LTE2IDE2em0wIDAiLz48cGF0aCBkPSJtMzY4IDI3Ny4zMzIwMzFoLTM1MmMtOC44MzIwMzEgMC0xNi03LjE2Nzk2OS0xNi0xNnM3LjE2Nzk2OS0xNiAxNi0xNmgzNTJjOC44MzIwMzEgMCAxNiA3LjE2Nzk2OSAxNiAxNnMtNy4xNjc5NjkgMTYtMTYgMTZ6bTAgMCIvPjwvc3ZnPg==") !important;
  }
  .navbar-light .not-collapsed .navbar-toggler-icon {
    background-image:url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjMxMXB0IiB2aWV3Qm94PSIwIDAgMzExIDMxMS4wNzczMyIgd2lkdGg9IjMxMXB0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Im0xNi4wMzUxNTYgMzExLjA3ODEyNWMtNC4wOTc2NTYgMC04LjE5NTMxMi0xLjU1ODU5NC0xMS4zMDg1OTQtNC42OTUzMTMtNi4yNS02LjI1LTYuMjUtMTYuMzgyODEyIDAtMjIuNjMyODEybDI3OS4wNjI1LTI3OS4wNjI1YzYuMjUtNi4yNSAxNi4zODI4MTMtNi4yNSAyMi42MzI4MTMgMHM2LjI1IDE2LjM4MjgxMiAwIDIyLjYzNjcxOWwtMjc5LjA1ODU5NCAyNzkuMDU4NTkzYy0zLjEzNjcxOSAzLjExNzE4OC03LjIzNDM3NSA0LjY5NTMxMy0xMS4zMjgxMjUgNC42OTUzMTN6bTAgMCIvPjxwYXRoIGQ9Im0yOTUuMTE3MTg4IDMxMS4wNzgxMjVjLTQuMDk3NjU3IDAtOC4xOTE0MDctMS41NTg1OTQtMTEuMzA4NTk0LTQuNjk1MzEzbC0yNzkuMDgyMDMyLTI3OS4wNTg1OTNjLTYuMjUtNi4yNTM5MDctNi4yNS0xNi4zODY3MTkgMC0yMi42MzY3MTlzMTYuMzgyODEzLTYuMjUgMjIuNjM2NzE5IDBsMjc5LjA1ODU5NCAyNzkuMDYyNWM2LjI1IDYuMjUgNi4yNSAxNi4zODI4MTIgMCAyMi42MzI4MTItMy4xMzY3MTkgMy4xMTcxODgtNy4yMzA0NjkgNC42OTUzMTMtMTEuMzA0Njg3IDQuNjk1MzEzem0wIDAiLz48L3N2Zz4=") !important;
  }
}

@media only screen and (max-width: 991px) and (min-width: 768px) {
  #nav-collapse .navbar-nav{
    margin-top: 16px;
    margin-left: 16px;
  }
}

@media only screen and (max-width: 767px) {
  .custom-button-container {
    display: block !important;
  }
  .custom-secondary {
    display: none !important;
  }
  .custom-footer-row-2 {
    display: none;
  }

  .custom-footer-row-4 {
    display: none;
  }

  .custom-footer-row-1 {
    flex: 0 0 100% !important;
    max-width: 100% !important;
    text-align: center;
  }

  .custom-null {
    display: none;
  }

  .custom-follow-us {
    flex: 0 0 100% !important;
    max-width: 100% !important;
    text-align: center;
  }

  .social-groups {
    text-align: center;
  }

  .row.custom-row {
    padding-top: 60px;
  }

  .heading-1 {
    font-size: 48px !important;
    line-height: 54px !important;
  }

  .content-1 {
    font-size: 16px !important;
    line-height: 26px !important;
  }

  .all-features {
    font-size: 14px;
  }

  .heading-4, .heading-3, .heading-5, .heading-6, .heading-7, .heading-8, .heading-9 {
    font-size: 28px !important;
    line-height: 36px !important;
  }

  .content-4, .content-3, .content-5, .content-6, .content-7, .content-8, .content-9 {
    font-size: 14px !important;
    line-height: 24px !important;
  }

  .compare-head-price {
    font-size: 18px !important;
    line-height: 29px !important;
  }

  .head-4 {
    font-size: 28px !important;
    padding-bottom: 20px !important;
    line-height: 36px;
  }
  .custom-form-control, .custom-form-control:focus {
    height: 44px !important;
    padding: 8px 16px 8px 16px !important;
  }
  #nav-collapse .navbar-nav{
    margin-top: 16px;
    margin-left: 8px;
  }
}

</style>
