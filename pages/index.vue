<template>
  <div class="wrapper">
    <div class="pshowcase">
      <div class="showcase container">
        <div class="pshowcase__txt">
          <h3>
            We solemnly pledge to transform your services 'so help us tech'.
          </h3>
          <div class="hbtn">
            <b-button size="lg" pill class="pill-1"
              ><nuxt-link
                style="color: white; text-decoration: none"
                to="/products&services"
                >Learn More</nuxt-link
              ></b-button
            >
          </div>
        </div>
        <div class="pshowcase__img">
          <b-img
            src="~/assets/img/descasio_big_bulb.svg"
            fluid-grow
            alt="Fluid-grow image"
            class="img pt-2"
            width="600vh"
          ></b-img>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="section2">
        <b-img
          src="~/assets/latrims/first_banner.png"
          fluid-grow
          alt="Fluid-grow image"
          class="hero img-fluid pt-3"
        ></b-img>
      </div>
    </div>
    <div class="container">
      <div class="section3_header">
        <p class="sub-heading">
          Here’s how we help your business <br />
          transform through technology
        </p>
        <hr />
      </div>
      <b-row class="section3">
        <b-col class="table-header">
          <div>
            <div class="section3_img">
              <b-img
                src="~/assets/latrims/latrims_table_banner.png"
                fluid-grow
                alt="Fluid image"
                class="idea-table img pt-3"
              ></b-img>
            </div>
          </div>
          <div class="section3b">
            <div class="side1">
              <div>
                <b-img
                  src="~/assets/img/descasio_reduce_cost.png"
                  alt="Fluid image"
                  srcset=""
                  class="reduced-costs img pt-2"
                ></b-img>
                <p class="here-how">DATA ANALYTICS & AI</p>
                <p class="here-how-sub">
                  Challenge your assumptions by turning information into insight
                  with our latest cloud, big data and predictive analytics
                  solutions..
                </p>
              </div>
              <div>
                <img
                  src="~/assets/img/descasio_efficiency_and_growth.png"
                  alt=""
                  srcset=""
                  class="reduced-costs img pt-2"
                />
                <p class="here-how">SECURITY SOLUTIONS</p>
                <p class="here-how-sub">
                  Our world class IT security solutions allows processes and
                  procedures to be in place to ensure that all information is
                  protected.
                </p>
              </div>
            </div>
            <div class="side2">
              <div>
                <img
                  src="~/assets/img/descasio_enhanced_security.png"
                  alt=""
                  srcset=""
                  class="reduced-costs img pt-2"
                />
                <p class="here-how">ERP</p>
                <p class="here-how-sub">
                  Improve performance, enhance productivity and drive growth
                  initiatives through automation of your business processes.
                </p>
              </div>
              <div>
                <img
                  src="~/assets/img/descasio_transparency_and_teamwork.png"
                  alt=""
                  srcset=""
                  class="reduced-costs img pt-2"
                />
                <p class="here-how">MANAGED SERVICE PROVIDERS</p>
                <p class="here-how-sub">
                  Choose how you deploy your cloud and on-premises with
                  consistent hybrid cloud capabilities using open source
                  technologies..
                </p>
              </div>
            </div>
          </div>
        </b-col>
      </b-row>
    </div>
    <div class="container">
      <div class="section4">
        <section>
          <div class="section4b">
            <p>Let’s make your business everything-proof</p>
            <!-- <b-icon icon="gear-fill" aria-hidden="true"></b-icon> -->
            <!-- <i class="fa fa-question"></i> -->
          </div>
        </section>
        <div style="margin-bottom: 2rem">
          <span style="border-top: 1px solid #e04b26; width: 100px">
            <b-button
              size="lg"
              pill
              class="pill-1"
              style="margin-top: 3rem; font-size: 15px"
            >
              <nuxt-link
                to="/contactUs"
                style="color: #fff; text-decoration: none"
                >Contact Us</nuxt-link
              >
            </b-button>
          </span>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="section5">
        <div class="cards cards1">
          <div class="cardA">
            <div class="card-img">
              <img
                src="~/assets/img/descasio_digital_transformation_icon_1.png"
                alt=""
                srcset=""
                class="reduced-costs img pt-2"
              />
            </div>
            <div class="services-title">
              <p>Digital Transformation</p>
            </div>
            <div class="services-text">
              <p>
                Latrim’s solution has unique capabilities to solve client’s
                digital problems, create long-term change
              </p>
            </div>
            <div>
              <p class="read-more">
                <nuxt-link to="/digitalTransformation" style="color: #e04b26"
                  >Read More</nuxt-link
                >
              </p>
            </div>
          </div>
          <div class="cardA">
            <div class="card-img">
              <img
                src="~/assets/img/descasio_security_optimization_icon.png"
                alt=""
                srcset=""
                class="reduced-costs img pt-2"
              />
            </div>
            <div class="services-title">
              <p>Security Optimization</p>
            </div>
            <div class="services-text">
              <p>
                Latrim’s solutions support the identification and elimination of
                all security risks that are <br />
                specific to the custom security needs of clients across all
                industries and business sizes
              </p>
            </div>
            <div>
              <p class="read-more">
                <nuxt-link to="/securityOptimization" style="color: #e04b26"
                  >Read More</nuxt-link
                >
              </p>
            </div>
          </div>
          <div class="cardA">
            <div class="card-img">
              <img
                src="~/assets/img/descasio_cloud_services_mgt_icon.png"
                alt=""
                srcset=""
                class="reduced-costs img pt-2"
              />
            </div>
            <div class="services-title">
              <p>Cloud Services Management</p>
            </div>
            <div class="services-text">
              <p>
                Latrim’s cloud services is positioned to deliver value to any
                business with tailored offerings
              </p>
            </div>
            <div class="read-more">
              <p>
                <nuxt-link to="/cloudServices" style="color: #e04b26"
                  >Read More</nuxt-link
                >
              </p>
            </div>
          </div>
        </div>
        <div class="cards">
          <div class="cardA">
            <div class="card-img">
              <img
                src="~/assets/img/technology_consulting_icon.png"
                alt=""
                srcset=""
                class="reduced-costs img pt-2"
              />
            </div>
            <div class="services-title">
              <p>Technology consulting</p>
            </div>
            <div class="services-text">
              <p>
                Latrim’s consulting expertise emphasizes continuous
                effectiveness of the company’s growth strategy.
              </p>
            </div>
            <div>
              <p class="read-more">
                <nuxt-link to="/technologyConsulting" style="color: #e04b26"
                  >Read More</nuxt-link
                >
              </p>
            </div>
          </div>
          <div class="cardA">
            <div class="card-img">
              <img
                src="~/assets/img/robotic_process_automation_icon.png"
                alt=""
                srcset=""
                class="reduced-costs img pt-2"
              />
            </div>
            <div class="services-title">
              <p>Robotic Process Automation</p>
            </div>
            <div class="services-text">
              <p>
                Latrim’s platform helps MSMEs build complex custom solutions
                faster, with higher quality.
              </p>
            </div>
            <div>
              <p class="read-more">
                <nuxt-link to="/roboticProcess" style="color: #e04b26"
                  >Read More</nuxt-link
                >
              </p>
            </div>
          </div>
          <div class="cardA">
            <div class="card-img">
              <img
                src="~/assets/img/descasio_reporting_analysis_icon.png"
                alt=""
                srcset=""
                class="reduced-costs img pt-2"
              />
            </div>
            <div class="services-title">
              <p>Analytics &amp; Reporting</p>
            </div>
            <div class="services-text">
              <p>
                Latrim’s consulting expertise emphasizes continuous
                effectiveness of the company’s growth strategy.
              </p>
            </div>
            <div class="read-more">
              <p>
                <nuxt-link to="/anayticsReporting" style="color: #e04b26"
                  >Read More</nuxt-link
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <b-container class="bv-example-row">
      <div class="section6">
        <div class="badges">
          <p>Our Partners & Clients</p>
        </div>
        <div class="partners">
          <img
            src="~/assets/partners/RE1Mu3b.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/Sophos.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/Google.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/Checkpoint.jpg"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/Zebra.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/AWS.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/Fortinet.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
          <img
            src="~/assets/partners/barracuda.png"
            alt=""
            srcset=""
            class="reduced-costs img pt-2"
          />
        </div>
      </div>

      <div class="section6b">
        <div class="badges">
          <p>Our Blogs</p>
        </div>
      </div>
      <div class="pb-4 blogs">
        <div class="article1">
          <div>
            <span style="color: #2b2d42" class="blogs-header">
              <nuxt-link to="#">BUSINESS MODEL</nuxt-link>,
              <nuxt-link to="#">DIGITAL TRANFORMATION</nuxt-link>
            </span>
            <div class="blogs-time">
              <time>June 9, 2024</time>
            </div>
            <h3 class="blogs-title">
              10 Most Powerful Business Technologies You Must Use to Stay
              Relevant By 2030
            </h3>
            <div class="blogs-text">
              <p>
                By 2030, ten powerful converging technologies will entirely
                transform how the way businesses work and engage with their
                customers. Here's what you need to know:
              </p>
            </div>
            <div class="bottombtn">
              <b-button pill variant="outline-secondary">Read more</b-button>
            </div>
          </div>
        </div>
        <div class="article1">
          <div class="blog-holder">
            <span style="color: #2b2d42" class="blogs-header">
              <nuxt-link to="#">DIGITAL TRANFORMATION</nuxt-link>
            </span>
            <div class="blogs-time">
              <time>May 26, 2024</time>
            </div>
            <h3 class="blogs-title">
              Reimagining Your Business In A Time of Blockchain
            </h3>
            <div class="blogs-text">
              <p>
                As Bitcoin and other cryptocurrencies have been picking up
                steam, the focus has turned to blockchain – the underlying
                distributed ledger technology (DLT) that powers these digital
                currencies. Blockchain technology is simple to understand…
              </p>
            </div>
            <div class="bottombtn">
              <b-button pill variant="outline-secondary">Read more</b-button>
            </div>
          </div>
        </div>

        <div class="article1">
          <div class="blog-holder">
            <span style="color: #2b2d42" class="blogs-header">
              <nuxt-link to="#">LIFESTYLE</nuxt-link>
            </span>
            <div class="blogs-time">
              <time>May 11, 2024</time>
            </div>
            <h3 class="blogs-title">10 Things You Need to Know About NFTs</h3>
            <div class="blogs-text">
              <p>
                Non Fungible Tokens (NFTS) are arguably the most interesting
                product in the blockchain space at the moment. Since the
                first-ever NFT, Quantum - sold last year for $1.4 million - was
                minted by Kevin McCoy in 2014, no one would have predicted,…
              </p>
            </div>
            <div class="bottombtn">
              <b-button pill variant="outline-secondary">Read more</b-button>
            </div>
          </div>
        </div>
      </div>
    </b-container>
    <b-container class="container">
      <div class="section7">
        <div class="section7a">
          <div class="section7-title">
            <p>For your daily dose of information subscribe now.</p>
          </div>
          <div>
            <form class="sub-form">
              <div class="form-group">
                <input
                  name="email address"
                  class="email-input"
                  type="text"
                  id="avia_0_1"
                  required
                  placeholder="Email Address*"
                />
                <button class="btn-danger btn-smt">Submit</button>
              </div>
            </form>
          </div>
        </div>
        <div class="section7b">
          <div class="get-holder">
            <div class="get-text">
              <p class="">Get Expert Services</p>
            </div>
            <div class="get-text-sub">
              <p class="">Lets help your business perform better</p>
            </div>
            <b-button class="get-button">
              <a href="#" class="" style="color: #fff">
                <span class="">
                  <nuxt-link
                    to="/contactUs"
                    style="color: #fff; text-decoration: none"
                    >Contact Us</nuxt-link
                  >
                </span>
              </a>
            </b-button>
          </div>
          <div class="img-section">
            <div>
              <div class="get-img">
                <img
                  src="~/assets/img/descasio_expert_services_illustration_1.png"
                  alt=""
                  width="103"
                  height="260"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="betslip">
        <b-button class="get-button">
          <a href="/contactUs" class="" style="color: #fff">
            <span class=""
              ><i style="font-size: 19px" class="fa fa-question"></i>&nbsp;
              Help</span
            >
          </a>
        </b-button>
      </div>
    </b-container>
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
hr {
  border: 1px solid #e04b26;
  width: 250px;
  position: relative;
  top: 162%;
  right: 40%;
  left: 3%;
}
.slider {
  /* width: 100%; */
  overflow: hidden;
  animation: slide 10s infinite;
}

.slider img {
  display: block;
  /* width: 100%; */
}

@keyframes slider {
  0% {
    transform: translate(0, 0);
  }
  33% {
    transform: translate(-1080px, 0);
  }
  66% {
    transform: translate(-2160px, 0);
  }
  100% {
    transform: translate(-3240px, 0);
  }
}
.partners {
  display: flex;
  gap: 1rem;
  /* display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: 1fr;
  font-size: 20px; */
  width: 900px;
  height: 80px;
  overflow: hidden;
  clear: both;
  position: relative;
  animation-name: slider;
  animation-duration: 30s;
  animation-delay: 10s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
  animation-direction: normal;
  animation-fill-mode: backwards;
  animation-play-state: running;
}

.partners img {
  /* height: 100px; */
  width: 100px;
  object-fit: fit;
  /* float: left; */
}

.pshowcase {
  background-image: url('~/assets/latrims/main_background.png');
  /* background-repeat: no-repeat; */
  background-position: cover;
  background-size: 100% 100%;
  /* padding-top: 116px; */
  /* height: 70vh; */
  color: #ffffff;
}
.pshowcase__txt > h3 {
  text-align: center;
  /* font-size: 16px; */
  font-size: clamp(0.9rem, 1vw + 1rem, 2.2rem);
  font-weight: 400;
  line-height: 1.2em;
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
@media screen and (min-width: 767px) {
  .pshowcase {
    background-image: url('~/assets/latrims/main_background.png');
    /* background-repeat: no-repeat; */
    background-position: cover;
    background-size: 100% 100%;
    /* padding-top: 116px; */
    height: 70vh;
    color: #ffffff;
  }
  /* .partners {
    display: flex;
  } */
  hr {
    border: 1px solid #e04b26;
    width: 250px;
    position: relative;
    top: 162%;
    right: 20% !important;
    left: 15%;
  }
  .showcase {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 20px;
  }
  .pshowcase__txt {
    width: 30%;
  }
  .pshowcase__img {
    width: 70%;
    /* padding-top: 3rem; */
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
  }
  .get-text {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: bold;
    line-height: 128%;
    color: #ffffff;
    max-width: 85%;
    font-size: 25px;
    margin-left: 15px;
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
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr;
    /* text-align: center !important; */
    align-content: center !important;
    align-items: center !important;
    gap: 5rem;
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
    white-space: normal;
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
  background-color: #e04b26;
  margin-top: 30px;
  padding: 15px 30px 13px;
  border: none;
}
.section3 {
  display: flex;
  gap: 2rem;
}
.section3b {
  /* display: table-cell; */
  display: flex;
  gap: 1rem;
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
.here-how {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 129%;
  color: #030404;
  text-align: left;
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
.section4 {
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
  background-image: url('https://www.descasio.io/wp-content/uploads/2020/10/descasio-light-curvy-bg.png');
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
}
.badges {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  line-height: 128%;
  color: #babada;
  font-size: 25px;
}
.blog-holder {
  margin-top: 1.5rem;
}
.blogs-header > a {
  color: #f18e78;
  font-size: 11.7px;
  font-weight: bold;
  top: 15px;
  font-family: 'Montserrat', sans-serif;
}
.blogs-time {
  /* display: inline-block; */
  font-size: 0.9em;
  color: #969696;
  font-family: 'Montserrat', sans-serif;
}
.blogs-title {
  color: #ffffff !important;
  vertical-align: baseline;
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 129%;
  text-transform: none;
  padding: 0;
  line-height: 1.3em;
  margin-bottom: 10px;
  margin-top: 15px;
  letter-spacing: 0;
}
.blogs {
  background: linear-gradient(
    115.55deg,
    #2b2d42 40.35%,
    rgba(70, 76, 132, 0.9) 98.2%
  );
  margin-top: 0;
  margin-bottom: 0;
  padding: 30px 0px 30px 0px;
  border-radius: 22px;
  background-position: 105% 4% !important;
  /* display: flex; */
}
.article1 {
  margin-left: 3%;
  padding-right: 3%;
  width: 100%;
  border-bottom: 1px solid #e04b2680;
}
.bottombtn {
  margin-bottom: 2rem;
}
.blogs-text {
  color: #c4c4df;
  font-size: 15px;
}
.section7-title {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 600;
  align-items: center;
  color: #2b2d42;
  font-size: 1.8rem;
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
  margin-left: -2rem;
  padding: 13px 3rem !important;
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
  height: 230px;
  background: linear-gradient(
    115.55deg,
    #2b2d42 40.35%,
    rgba(70, 76, 132, 0.9) 98.2%
  );
  display: flex;
  justify-content: space-between;
  padding-top: 3rem;
  border-radius: 22px;
  margin-top: 20px;
  padding: 30px;
}

.get-text {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  line-height: 128%;
  color: #ffffff;
  max-width: 85%;
  font-size: 25px;
  margin-left: 15px;
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
  margin-left: 15px;
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
