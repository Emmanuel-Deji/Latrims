<template>
  <div class="wrapper">
    <div class="pshowcase">
      <div class="showcase container">
        <div class="pshowcase__txt">
          <div style="display: flex; gap: 3px; margin-bottom: -0.5 !important">
            <!-- <b-img
              src="~/assets/digitalTransformation/Digital-Transformation-icon-36x36.png"
              alt="Fluid image"
              srcset=""
              class="reduced-costs img pt-2"
            >
            </b-img> -->
            <h1 class="digital">Contact Us</h1>
          </div>
          <hr class="dthr" />
          <h3 class="digitaltext">
            We are here to answer any questions you may have. Reach out to us and we’ll respond as soon as we can.
          </h3>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="where">
        You are here: <a href="/" style="color: #e04b26">Home</a> / Digital
        Transformation
      </div>
    </div>
    <div class="container">
      <b-row class="section3">
        <b-col class="table-header">
          <div class="btw">
          <div class="section3b">
            <div class="subholder">
              <h3 class="header">Connect With Us</h3>
            </div>
            <div class="subholder">
              <h4 class="subhead">Address</h4>
              <div>15 Fubara Dublin Green St. Igbo Efon, Lekki, Lagos, Nigeria</div>
            </div>
            <div class="subholder">
              <h3 class="subhead">Email</h3>
              <a href="mailto:saorim@latrims.com.ng">saorim@latrims.com.ng</a>
            </div>
            <div class="subholder">
              <h3 class="subhead">Phone</h3>
              <a href="tel:+2347059031942">+2347059031942</a>
            </div>
            <div style="display: flex;">
              <i
              style="margin-right: 1rem; font-size: 35px;  color: #BABADA;"
              class="fa fa-whatsapp"
              aria-hidden="true"
              ></i>
              <h3>Message us on WhatsApp</h3>
            </div>

            <div style="font-size: 25px;  color: #BABADA;"> <i
            style="margin-right: 1rem"
            class="fa fa-facebook"
            aria-hidden="true"
          ></i
          >&nbsp;
          <i
            style="margin-right: 1rem"
            class="fa fa-instagram"
            aria-hidden="true"
          ></i
          >&nbsp;
          <i
            style="margin-right: 1rem"
            class="fa fa-linkedin"
            aria-hidden="true"
          ></i
          >&nbsp;
          <i
            style="margin-right: 1rem"
            class="fa fa-twitter"
            aria-hidden="true"
          ></i></div>
            
          </div>
          <!-- <div class="homehere">You Sare here:Home/Digital Transformation</div> -->
          <div>
            <form>
              <div style="display: flex; gap: 1rem;">
                <p>
                  <label for="fname" class="form_title"> Full Name <span style="color: #e04b26;">*</span></label>
                  <input name="fname" class="input" type="text" id="fname" value />
                </p>
                <p>
                  <label for="contact_num" class="form_title"> Contact Number <span style="color: #e04b26;">*</span></label>
                  <input name="contact_num" class="input" type="text" id="contact_num" value />
                </p>
              </div>
              <div>
                <p>
                  <label for="company_name" class="form_title"> Company Name <span style="color: #e04b26;">*</span></label> <br>
                  <input name="company_name" class="input" type="text" id="company_name" value />
                </p>
              </div>
              <div>
                <p>
                  <label for="job_tit" class="form_title"> Job Title <span style="color: #e04b26;">*</span></label><br>
                  <input name="job_tit" class="input" type="text" id="job_tit" value />
                </p>
              </div>
              <div style="display: flex; gap: 1rem;">
                <p>
                  <label for="email" class="form_title"> E-Mail Address <span style="color: #e04b26;">*</span></label>
                  <input name="email" class="input" type="text" id="email" value />
                </p>
                <p>
                  <label for="indust" class="form_title"> Industry <span style="color: #e04b26;">*</span></label>
                  <select name="indust">
                    <option value="Financial Services">Financial Services</option>
                    <option value="Oli and Gas">Oil and Gas</option>
                    <option value="Aviation">Aviation</option>
                    <option value="Manufacturing">Manufactuing</option>
                    <option value="Telecommunications">Telecommunications</option>
                    <option value="Real Estate">Real Estate</option>
                    <option value="Transportation & Logistics">Transportation & Logistics</option>
                    <option value="Health & other Social Services">Health & other Social Services</option>
                    <option value="Public Sector">Public Sector</option>
                    <option value="Other">Other</option>
                  </select>
                </p>
              </div>
              <div>
                <p>
                  <label for="message" class="form_title"> Message <span>*</span></label> <br>
                  <textarea rows="4" cols="50" name="message" id="message" placeholder="Enter your message here..."></textarea>
                </p>
              </div>
              <div>
                <button type="submit">Send Message</button>
              </div>
              <div>This site is protected by reCAPTCHA and the Google Privacy Policy and Terms of Service apply.</div>
            </form>
          </div>
        </div>
          <div>
            <div class="section7b">
              <div class="get-holder">
                <div class="get-text">
                  <p class="">If in doubt click here</p>
                </div>
                <div class="get-text-sub">
                  <p class="">Lets help your business perform better</p>
                </div>
                <b-button class="get-button">
                  <a href="#" class="" style="color: #fff">
                    <span class="">Click here</span>
                  </a>
                </b-button>
              </div>
            </div>
          </div>
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<!-- <script>
  export default {
    name: 'IndexPage',
  }
  </script> -->

<style scoped>
*,
::before,
::after {
  box-sizing: border-box;
}
.card-img {
  text-align: center;
}
.subhead {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 128%;
    color: #BABADA;
}
.subholder {
  margin-bottom: 1.5rem;
}
.subholder >a {
  color: #e04b26;
}

.form_title {
    font-weight: bold;
    font-size: 0.92em;
    color: #474870!important;
}
form {
    background: #ffffff;
    box-shadow: 0 0 10px 0 #d0d0d0;
    padding: 30px;
    background-color: #ffffff;
    border-radius: 20px;
}
.input{ 
    background-color: #f18e7829 !important;
    width: 100%;
}
.where {
  text-align: right;
}
.num {
  color: #babada;
  font-size: 71px;
  font-weight: bold;
}
.where {
  text-align: right;
}
.digital {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 400;
  line-height: 129%;
  color: #babada;
}
hr {
  border: 1px solid #e04b26;
  width: 250px;
  position: relative;
  top: 162%;
  right: 40%;
  left: 3%;
}
.dthr {
  border: 1px solid #e04b26;
  width: 380px;
  position: relative;
  top: 162%;
  right: 40%;
  left: -20%;
}
.dita {
  display: flex;
  /* gap: 2rem; */
  margin-bottom: 3rem;
  margin-top: 1rem;
}
.form-group {
  display: flex;
}
.pshowcase {
  background-image: url('~/assets/contactUs/contact-us.png');
  /* background-repeat: no-repeat; */
  background-position: cover;
  background-size: 100% 100%;
  /* padding-top: 116px; */
  height: 55vh;
  color: #ffffff;
}
.pshowcase__txt > h3 {
  text-align: center;
  font-size: 16px;
  /* font-size: clamp(0.9rem, 1vw + 1rem, 2.2rem); */
  font-weight: 300;
  line-height: 1.2em;
  width: 100%;
}
.pshowcase__txt {
  margin-top: 5rem;
}
.showcase {
  padding-top: 50px;
}
.hbtn {
  display: flex;
  justify-content: center;
  align-items: center;
}
@media (min-width: 767px) {
  .pshowcase {
    background-image: url('~/assets/contactUs/contact-us.png');
    /* background-repeat: no-repeat; */
    background-position: cover;
    background-size: 100% 100%;
    /* padding-top: 116px; */
    height: 70vh;
    color: #ffffff;
  }
  .btw{
    display:flex;
  }
  hr {
    border: 1px solid #e04b26;
    width: 250px;
    position: relative;
    top: 162%;
    right: 20% !important;
    /* left: 15%; */
  }
  .showcase {
    display: flex;
    /* justify-content: center; */
    align-items: center;
    padding-top: 116px;
    margin-left: 8rem;
  }
  .pshowcase__txt {
    width: 54%;
    margin-top: 4rem;
  }
  .digitaltext {
    color: #d7d7e2;
    font-size: 18px !important;
    font-weight: 900;
  }
  .pshowcase__img {
    width: 70%;
  }
  .pshowcase__txt > h3 {
    text-align: left;
  }
  .hbtn {
    display: block;
  }
  .blogs {
    background: linear-gradient(
      115.55deg,
      #2b2d42 40.35%,
      rgba(70, 76, 132, 0.9) 98.2%
    );
    display: flex;
    margin-top: 0;
    margin-bottom: 0;
    padding: 30px 0px 30px 0px;
    border-radius: 22px;
    background-position: 105% 4% !important;
  }
  .article1 {
    margin-left: 3%;
    padding-right: 3%;
    width: 100%;
    border-right: 1px solid #e04b2680;
    border-bottom: none !important;
  }
  .blog-holder {
    margin-top: 0 !important;
  }
  .cards {
    display: flex;
  }
  .section7 {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr;
    gap: 5rem;
  }
  .get-text {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: bold;
    line-height: 128%;
    color: #ffffff;
    max-width: 85%;
    font-size: 25px;
    margin-left: -16px;
    margin-top: 20px !important;
  }
  .get-text-sub {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 300;
    line-height: 128%;
    text-align: left;
    color: #ffffff;
    margin-top: -20px !important;
    max-width: 85%;
    margin-left: 15px;
  }
  .table-header {
    /* display: grid; */
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr;
    /* text-align: center !important; */
    align-content: center !important;
    align-items: center !important;
    gap: 3rem;
  }
  .section3_header {
    font-size: 20px;
    font-family: 'Montserrat', sans-serif;
    font-weight: bold;
    color: #2b2d42;
    line-height: 131%;
    text-align: center;
    margin-left: 10px;
  }
  /* .section{
      text-align: center !important;
    } */
  .side1,
  .side2 {
    margin-bottom: 5rem;
  }
  .sub-heading {
    text-align: right !important;
    padding-right: 180px;
    width: 100%;
    padding-left: 0rem;
    align-items: center;
  }
  .idea-table {
    margin-top: -150px;
    /* height: 90vh; */
  }
}

p {
  margin: 0.85em 0;
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}

.hero {
  width: 100%;
  margin: 0 auto;
  height: 430vm;
  display: flex;
}
.pill-1 {
  margin-top: 30px;
  padding: 15px 30px 13px;
  text-align: center;
  font-style: normal;
  font-weight: normal;
  line-height: 128%;
  color: #2b2d42;
}
.section3 {
  display: flex;
  gap: 2rem;
}
.section3b {
  /* display: table-cell; */
  /* display: flex; */
  gap: 10rem;
  /* width: 100%; */
}
.section3_header {
  margin-top: 3rem;
  font-size: 20px;
  font-family: 'Montserrat', sans-serif;
  font-weight: bold;
  color: #2b2d42;
  line-height: 131%;
  padding: 0 10px 0 10px;
  text-align: center;
  /* border-bottom: 1px solid #e04b26; */
}
.here-top {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 129%;
  color: #2b2d42;
  text-align: left;
  padding-right: 15px;
  /* border-bottom: 1px solid #e04b26; */
}
.here-how {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 129%;
  color: #2b2d42;
  text-align: left;
  padding-right: 15px;
  border-bottom: 1px solid #e04b26;
}
.here-how-sub {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 128%;
  text-align: left;
  color: #2b2d42;
}
.section4b {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  line-height: 131%;
  align-items: center;
  color: #2b2d42;
  font-size: 30px;
  text-align: center;
}
.cards1 {
  margin-bottom: 3rem;
}
.cards {
  /* display: flex; */
  cursor: pointer;
  gap: 1rem;
  text-align: center;
  float: none;
  /* display: table-cell; */
  background-image: url(https://www.descasio.io/wp-content/uploads/2020/10/descasio-light-curvy-bg.png);
}
.cardA {
  background: #ffffff;
  box-shadow: 0 0 10px 0 rgb(0 0 0 / 11%);
  padding: 50px 30px 50px 30px;
  background-color: #ffffff;
  border-radius: 22px;
  transition: transform 0.3s;
  margin-bottom: 2rem;
  /* animation: avia-ttb 0.8s 1 cubic-bezier(0.175, 0.885, 0.320, 1.275); */
}
.cardA:hover {
  transform: translateY(-10px);
  box-shadow: 5px 5px 10px 5px rgb(0 0 0 / 11%);
}
.services-title {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 128%;
  color: #2b2d42;
  text-align: center;
}
.services-text {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 144%;
  text-align: center;
  color: rgba(0, 0, 0, 0.6);
}
.read-more {
  color: #e04b26;
  font-weight: bold;
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  text-align: center;
}

.badgesY {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  line-height: 128%;
  color: #030404;
  font-size: 25px;
  text-align: center;
}

.email-input {
  background: #babada !important;
  color: #2b2d42;
  border: none !important;
  border-radius: 0px !important;
  outline: none;
  font-size: 13px;
  font-family: 'Montserrat', sans-serif;
  padding: 13px;
  width: 60%;
}
.btn-smt {
  outline: none;
  border-radius: 30px;
  background-color: #e04b26;
  color: #ffffff;
  border: none;
  margin-left: 46px;
  padding: 10px 2rem !important;
  font-size: 13px;
  font-family: 'Montserrat', sans-serif;
  font-weight: bold;
}
.btn-smit {
  outline: none;
  border-radius: 30px;
  background-color: #e04b26;
  color: #ffffff;
  border: none;
  /* margin-left: 46px; */
  padding: 10px 2rem !important;
  font-size: 13px;
  font-family: 'Montserrat', sans-serif;
  font-weight: bold;
}
input[type='text'] {
  -webkit-appearance: none;
  border-radius: 0px;
  border: none !important;
  outline: none;
}
fieldset {
  display: flex;
  gap: 6.5srem;
}
.button {
  background-color: #e04b26;
  color: #ffffff;
  border-color: #c02904;
  border-radius: 30px;
  border-bottom-width: 1px;
  border-bottom-style: solid;
  min-width: 142px;
  outline: none;
  margin-left: -10px;
  margin-top: 0px;
  height: 43px;
  /* padding: 12px 20px!important; */
  font-weight: bold !important;
  font-size: 15px !important;
  font-weight: bold;
}
/* .section7 {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr; 
  } */
.section7b {
  /* height: 385px; */
  background: linear-gradient(
    115.55deg,
    #2b2d42 40.35%,
    rgba(70, 76, 132, 0.9) 98.2%
  );
  /* display: flex; */
  /* justify-content: space-between; */
  padding-top: 3rem;
  border-radius: 22px;
  margin-top: 20px;
  padding: 30px;
  margin-right: 1rem;
}

.get-text {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  line-height: 128%;
  color: #ffffff;
  max-width: 85%;
  font-size: 25px;
  margin-left: -10px;
  margin-top: -20px;
}
.get-text-sub {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 300;
  line-height: 128%;
  text-align: left;
  color: #ffffff;
  margin-top: -20px;
  max-width: 85%;
  margin-left: -10px;
}
.get-button {
  border-radius: 30px;
  background-color: #e04b26;
  color: #ffffff;
  border-color: #c02904;
  margin-left: 15px;
  padding: 10px;
}
.betslip {
  font-family: 'Montserrat', sans-serif;
  font-weight: 900;
  z-index: 110;
  display: flex;
  position: fixed;
  bottom: 70px;
  justify-content: center;
  right: 0;
  padding: 5px;
  text-align: center;
  border-top-left-radius: 0.5rem;
  border-bottom-left-radius: 0.5rem;
  font-size: 12px;
  flex-direction: column;
  align-items: center;
  gap: 4px;
}
</style>
