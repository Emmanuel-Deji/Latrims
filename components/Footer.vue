<template>
  <div class="footer">
    <div class="footer1">
      <div class="footer-text">
        <p class="logo-text">
          Latrims
          <span style="color: #ffffff66"> Nigeria </span>
        </p>
        <p class="footer-sub-text">
          Latrims is a company leading the revolutionary approach to Information
          Communication Technology (ICT) by redefining and reimagining strategic
          approach to solutions and services delivery. We are focused on the
          provision of Information Technology Solutions and Services that are
          built on a world-class, secure, resilient infrastructure, delivered
          according to global best practices in partnership with the world’s
          leading technology vendors .
        </p>
      </div>
      <div class="footer-list">
        <div class="listed">
          <div class="contact-list">
            <p class="contact">Have a Questions?</p>
            <div class="contact-list">
              <p class="underline">
                10 Fubara dublin green st. igbo efon, Lekki, Lagos, Nigeria
              </p>
              <p class="underline">+234815980544</p>
              <p class="underline">
                <i class="fa fa-envelope" aria-hidden="true">&nbsp;</i
                >saorim@latrims.com.ng
              </p>
            </div>
          </div>
          <div class="contact-list">
            <p class="contact">Quick Links</p>
            <div class="contacts">
              <p class="underline">About Us</p>
              <p class="underline">Products and Services</p>
              <p class="underline">Contact Us</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer2">
      <div>
        <p>Copyright © 2022 All rights reserved Latrims</p>
      </div>
      <div class="icon">
        <span class="smicon" style="font-size: 25px; color: #ebebeb;">
          <i style="margin-right: 1rem;" class="fa fa-facebook" aria-hidden="true"></i>&nbsp;
          <i style="margin-right: 1rem;" class="fa fa-instagram" aria-hidden="true"></i>&nbsp;
          <i style="margin-right: 1rem;" class="fa fa-linkedin" aria-hidden="true"></i>&nbsp;
          <i style="margin-right: 1rem;" class="fa fa-twitter" aria-hidden="true"></i>&nbsp;
          <i style="margin-right: 1rem;" class="fa fa-youtube" aria-hidden="true"></i>&nbsp;
          <i style="margin-right: 1rem;" class="fa fa-whatsapp" aria-hidden="true"></i>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@media (min-width: 767px) {
  .footer {
    box-sizing: border-box;
    height: 70vh;
  }
  /* .smicon{ 
    width: 100% !important;
  } */
  .footer1 {
    width: 100%;
    height: none;
    border: 1px solid red;
    background-size: 100% 100% !important;
    /* background-position: cover; */
    justify-content: center;
    align-items: center;
    gap: 10rem;
    /* margin-top: 7rem; */
    outline: none;
    border: none;
    border-color: #ebebeb;
    color: #ffffff;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr;
  }
  .footer2 {
    display: flex;
    gap: 15rem;
  }
  .icon {
    margin-top: 10px;
    transition: transform 0.3s;
  }
  .icon :hover{
    transform: translateY(-5px);
  }
  .logo-text,
  .footer-sub-text {
    display: contents !important;
    margin-bottom: 0;
  }
  .logo-text {
    display: flex !important;
  }
  .logo-text {
    font-size: 3.5rem;
    padding-left: 1rem;
    font-weight:  bold;
  }
  .footer-sub-text {
    padding-right: 200px;
    font-family: 'Montserrat', sans-serif;
  }
  .footer-list {
    text-align: center !important;
    align-items: center !important;
    justify-content: center !important;
    display: flex !important;
    /* display: table-column-group; */
    display: table-row;
  }
  .footer-text {
    display: grid !important;
  }
  .contact-list {
    font-family: 'Montserrat', sans-serif;
    font-size: 15px;
    border-bottom: none !important;
    margin-bottom: 1rem;
  }
  .listed {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr;
    gap: 2rem;
  }
  .contact {
    font-size: 18px !important;
  }
}

/* Moblie screen */

.footer {
    box-sizing: border-box;
    height: 0vh !important;
  }
.footer1 {
  /* background-image: url('https://www.descasio.io/wp-content/uploads/2020/10/descasio-footer-fade.png'), linear-gradient(to bottom, white 10%, #3e4063); */
  background-image: url('https://www.descasio.io/wp-content/uploads/2020/10/descasio-footer-fade.png'),  linear-gradient(to bottom, white, #3e4063, #3e4063);
  background-repeat: no-repeat;
  /* background-position: cover; */
  background-size: 100% 50%;
  background-color: #3e4063;
  height: 60vh;
  /* gap: 10rem; */
  margin-top: 7rem;
  outline: none;
  /* border: 2px solid red; */
  /* border-color: #ebebeb; */
  color: #ffffff;
  /* display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr; */

}

p {
  margin: 0.85em 0;
}
.logo-text {
  font-size: 3.5rem;
  padding-left: 1rem;
}
.footer-text {
  padding-left: 100px;
}
.footer-list {
  /* display: flex; */
  /*margin-top: 10rem; */
  gap: 2rem;
  padding-right: 5rem;
  padding-left: 1rem;
  text-align: left;
  align-items: left;
}
.logo-text,
.footer-sub-text {
  display: none;
}

.contact-list {
  font-family: 'Montserrat', sans-serif;
  font-size: 15px;
  /* border-bottom: 1px solid #e04b26; */
  margin-bottom: 1rem;
}
p.underline {
  border-bottom: 1px solid #e04b26;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
}
.contacts {
  margin-top: 2rem;
}
.contact {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 25px;
  line-height: 24px;
  color: #ffffff;
  padding-bottom: 1rem;
  margin-top: 3rem;
}

.footer2 {
  background: #2b2d42;
  background-color: #2b2d42;
  padding: 5px 5px 5px 5%;
  color: #ffffff;
}
.icon {
  text-align: right;
  margin-right: 13px;
  transition: transform 0.3s;
}
</style>
