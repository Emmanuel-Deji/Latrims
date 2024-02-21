<template>
  <div class="header">
    <b-navbar toggleable="lg" type="dark" class="container-fluid bar">
      <nuxt-link to="/" class="logo">
        <b-navbar-brand class="logo">
          <!-- <span style="color: #ffffff66"><span style="color: #fff">Latrims</span>Nigeria</span> -->
          <img
                src="~/assets/latrims/latrim_logo4.jpg"
                alt=""
                srcset=""
                class=""
              />
        </b-navbar-brand>
      </nuxt-link>
      <!--  -->
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- <div class="nav_menu"> -->
        <b-navbar-nav class="ml-auto">
          <div class="dropdown">
            <li class="dropbtn" style="text-decoration: none !important">
              <a
                href="/aboutUs"
                style="text-decoration: none !important"
                >About us</a
              >
            </li>
            <div class="dropdown-content">
              <nuxt-link :to="'/aboutUs#mission'"> Mission, Vision & Value</nuxt-link>
              <nuxt-link :to="'/aboutUs#management'">Leadership</nuxt-link>
              <nuxt-link :to="'/aboutUs#partners'" class="last-list">Partners & Clients</nuxt-link>
            </div>
          </div>
          <div class="dropdown">
            <li class="dropbtn">What We Do</li>
            <div class="dropdown-content">
              <a href="/digitalTransformation"> Digital Transformation</a>
              <a href="/securityOptimization"> Security Optimization</a>
              <a href="/cloudServices">Cloud Services Management</a>
              <a href="/roboticProcess">Robotic Process Automation</a>
              <a href="/technologyConsulting">Technology Consulting</a>
              <a href="/anayticsReporting">Analytics &amp; Reporting</a>
              <a href="/products&services" class="last-list"
                >All Products &amp; Services</a
              >
            </div>
          </div>
          <div class="dropdown">
            <li class="dropbtn">Resources</li>
            <div class="dropdown-content">
              <!-- <a href="/marketplace">Marketplace</a> -->
              <a href="/blog">Blog</a>
              <a href="#" class="last-list">Customer Success Stories</a>
            </div>
          </div>
          <div class="dropdown">
            <li class="dropbtn" style="text-decoration: none !important">
              <a
                href="/careers"
                style="text-decoration: none !important"
                >Careers</a
              >
            </li>
            <!-- <div class="dropdown-content">
              <a href="#" class="last-list">Contact Us</a>
            </div> -->
          </div>
          <b-button pill style="background-color: #e04b26"><a
                href="/contactUs"
                style="text-decoration: none !important"
                >Contact Us</a
              ></b-button>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.header {
  position: fixed;
  width: 100%;
  z-index: 99;
}
a {
  font-size: 12px;
  color: #fff;
  /* background-color: #2b2d42; */
}
.dropbtn > a {
  font-size: 16px;
  color: #fff;
}
.dropdown {
  position: relative;
  display: inline-block;
}
li > dropbtn {
  text-decoration: none;
}
.ml-auto {
  /* padding-top: 2rem; */
  padding-right: 8rem;
}
.dropdown-content {
  display: none;
  position: absolute;
  /* background-color: #f1f1f1; */
  min-width: 180px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  border-radius: 8px;
  border: 2px solid #2b2d42;
  margin: 0.5rem;
  width: 15px;
  font-family: 'Montserrat', sans-serif;
  background-color: #2b2d42;
  animation-delay: 2s;
}
.dropbtn {
  background-color: transparent;
  color: white;
  /* padding: 16px; */
  /* font-size: 16px; */
  border: none;
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  padding-right: 2rem;
  font-weight: 700;
  text-decoration: none;
}
.dropbtn:hover {
  border-bottom: 1px solid #e04b26;
  text-decoration: none !important;
  transition-delay: 2s;
}
.dropdown-content a {
  color: #fff;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  border-bottom: 1px solid rgb(107, 102, 102);
  font-size: 12px;
}
.last-list {
  border-bottom: 0;
}
.dropdown-content > a:hover {
  background-color: #e04b26;
}
.dropdown-content:hover {
  transition-delay: 5s;
}

.dropdown:hover .dropdown-content {
  display: block;
  text-decoration: none !important;
}

/* .dropdown:hover .dropbtn {background-color: #3e8e41;} */
li {
  padding-left: 10px;
  padding-right: 10px;
  text-decoration: none;
  list-style-type: none;
  cursor: pointer;
  color: white;
  font-size: 1.3vw;
}
.link {
  text-decoration: none;
  list-style-type: none;
  color: white;
  padding: 36px 15px;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 700;
}
.bar {
  display: flex;
  justify-content: space-around;
  background: #2b2d42;
  color: #fff;
  padding-top: 1rem;
  padding-bottom: 0.5rem;
  text-align: center;
  align-items: center;
  padding-left: 3rem;
  /* position: fixed; */
  /* background-color: transparent; */
}
/* .menu {
  font-weight: 400;
  font-size: 15px;
  display: flex;
  list-style: none;
  justify-content: space-around;
} */
.logo {
  color: #fff;
  font-size: 25px;
  font-weight: 700;
  position: relative;
  text-decoration: none;
  font-family: 'Montserrat', sans-serif;
  padding-left: 0rem;
}
button {
  font-family: 'Montserrat', sans-serif;
}
</style>
