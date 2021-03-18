<template>
    <section>
        <section>
      <div class="container">
        <div class="pricing-head-block">
          <div class="contact-header">
            The journey of billion miles begin with a thoughtful First MileLead the way, Think Settyl
          </div>
        </div>
      </div>
    </section>


    <section style="background: #fff">
      <div class="container contact-info">
        <div class="row">
          <div class="col-sm-12 col-lg-6">
            <div class="call-sales">
              <img src="../assets/phone.svg" alt="Call Sales" width="66" height="64">
              <div class="support-block">
                <div class="sales-head">
                  Call Sales
                </div>
                <div class="sales-content">
                  Interested in any of our products?<br>Talk to our experts today.
                </div>
                <div class="sales-contact-no">
                  Toll Free : <span style="font-weight: 600;">+1 888.936.8638</span><br>
                  Phone : <span style="font-weight: 600;">+1 919.481.1974</span>
                </div>
              </div>
            </div>

            <div class="support-enquiry">
              <img src="../assets/address.svg" alt="Support Enquiry" width="66" height="64">
              <div class="support-block">
                <div class="support-head">
                  Support Queries
                </div>
                <div class="support-content">
                  Using any of our products and need help? <br>
                  Get in touch with customer support.
                </div>
                
                <div class="contact-read">
                  <a href="#">
                    Read more<i class="fas fa-angle-right"></i>
                  </a>
                </div>
              </div>
              
            </div>
          </div>

          <div class="col-sm-12 col-lg-6">
            <div class="card contact-card">
              <div class="card-body contact-card-body">
                <h5 class="card-title contact-card-title">Send us a message</h5>
                <div class="input-group mb-3">
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
                  placeholder="Phone Number"
                  aria-label="Phone Number"
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
              </div>
              <div class="input-group mb-3 agreement">
                <input
                  type="checkbox"
                  class="form-control contact-checkbox"
                  aria-describedby="basic-addon2"
                  :checked="isAgreeCheck"
                  v-model="isAgreeCheck"
                />
                <div class="terms">I agree to account creation and I have read and agree to the Terms of Use, Cookie Policy and Privacy Policy.</div>
              </div>
                <a @click="handleFormSubmit" class="btn btn-primary custom-contact-btn" v-bind:class="isAgreeCheck ? '' : 'disabled'" >Submit</a>
                <div class="secure">This site is protected by reCAPTCHA and the Google <span style="color: #FF4702;">Privacy Policy</span> and <span style="color: #FF4702;">Terms of Service</span> apply.</div>
                <div v-if="isFormSubmitted" class="success_msg">Form is submitted successfully.</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

   

    </section>
</template>

<style>
.success_msg {
  border: 1px solid;
  border-color: #0565FF;
  border-radius: 6px;
  padding: 7px 0;
  margin-top: 20px;
  background: #F0F7FF;
  color: #007aff;
}
.pricing-head-block {
  margin: 180px 0 66px 0;
  padding: 0 8%;
}

.contact-header {
  font-size: 40px;
  text-align: center;
  line-height: 56px;
  color: #141d30;
  font-weight: 700;
  margin-bottom: 24px;
}

.content-desc {
  font-weight: 400;
  font-size: 16px;
  line-height: 32px;
  color: #283a5e;
  text-align: center;
}

.switch-toggle {
  margin-bottom: 40px;
}

.contact-card {
  border: none !important;
  box-shadow: 0px 0px 15px 0px #0059b126 !important;
  width: 100% !important;
}

.contact-card .contact-card-body {
  padding: 50px 40px !important;
  text-align: center;
}

.contact-card-title {
  font-size: 26px;
  font-weight: 600;
  color: #283a5e;
  margin-bottom: 30px;
}

.contact-info {
  padding: 70px 0 120px;
}
.office-tile-card {
    border: 1px solid #d3e2ed;
    box-sizing: border-box;
    box-shadow: 0px 4px 14px rgba(30, 69, 102, .06);
    border-radius: 4px;
        max-width: 100% !important;
    margin: auto !important;
}
.contact-card-text {
  color: #283a5e;
  margin-bottom: 20px;
}

.contact-input {
  height: 44px;
}

.contact-multi-line {
  height: 120px !important;
}

.contact-checkbox {
  width: 13px !important;
  height: 13px !important;
  display: inline;
}

.terms {
  display: inline;
  padding-left: 8px;
}

.custom-contact-btn, .custom-contact-btn:hover, .custom-contact-btn:focus, .custom-contact-btn:active{
  width: 100%;
  height: 48px;
  padding: 12px;
  background-color: #ff4800 !important;
  border: none;
}

.secure {
  font-size: 14px;
  text-align: center;
  margin: 20px auto 0;
  padding: 0 50px;
  color: #68758E;
}

.agreement {
  display: inline-block;
  margin-top: 20px;
  margin-bottom: 30px !important;
}



.sales-block {
  display: inline-table;
  margin-left: 34px;
  padding: 70px 0;
}

.sales-head, .support-head {
  font-size: 28px;
  color: #141D30;
  font-weight: 600;
}

.sales-content, .support-content {
  padding: 20px 0;
  font-size: 18px;
  color: #283A5E;
}

.sales-contact-no {
  font-size: 18px;
  color: #283A5E;
}



.contact-read a {
  color: #FE4901;
  position: relative;
  font-size: 18px;
  text-decoration: none;
  font-weight: 500;
}

.contact-read i {
  position: absolute;
  top: 3px;
  margin-left: 6px;
}

.contact-read i.fas.fa-angle-right {
  
  background-repeat: no-repeat;
  width: 14px;
  height: 14px;
  line-height: 24px;
  margin-top: 2px;
}

.support-block {
  display: inline-table;
  margin-left: 34px;
  padding: 40px 0;
}

.location {
  font-weight: 700;
  font-size: 42px;
  color: #141D30;
  text-align: center;
  padding: 80px 0 40px;
}

.location-card .card-title {
  font-size: 20px;
  font-weight: 600;
  padding-bottom: 10px;
  color: #283a5e;
}

.location-card .card-text {
  color: #283a5e;
  line-height: 28px;
  font-size: 16px;
}

.location-card {
  padding-bottom: 80px;
}

.card-body {
  text-align: left;
  padding: 20px !important;
}

@media only screen and (max-width: 1024px) and (min-width: 768px) {
.contact-info{
  padding: 12px;
}
.pricing-head-block{
      margin: 140px 0 32px 0;
}
.contact-header {
  font-size: 40px;
  line-height: 48px;
}
}
@media only screen and (max-width: 992px) and (min-width: 767px) {
.contact-info{
  padding: 12px;
}
.contact-card .contact-card-body{
  padding: 20px 32px !important;
}
}
@media only screen and (max-width: 767px) and (min-width: 320px) {
.contact-info{
  padding: 40px 16px !important;
}
.contact-card .contact-card-body{
  padding: 20px 16px !important;
}
.pricing-head-block{
      margin: 140px 0 32px  0;
}
.contact-header {
  font-size: 40px;
  line-height: 48px;
}
}

@media only screen and (max-width: 512px) and (min-width: 460px){
.support-block {
    margin-left: 0px;
}
}
@media only screen and (max-width: 459px) and (min-width: 320px){
.support-block {
    margin-left: 0px;
}
}

@media only screen and (max-width: 1024px) and (min-width: 768px) {
.tab-display-n {
    display: none !important;      
 }
}

@media only screen and (max-width: 767px) and (min-width: 320px) {
.mbl-display-n {
    display: none !important;      
 }
}
</style>
