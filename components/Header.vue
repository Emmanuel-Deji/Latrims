<template>
  <div class="header">
    <b-navbar toggleable="lg" type="dark" class="container-fluid bar">
      <nuxt-link to="/" class="logo">
        <b-navbar-brand class="logo">
          Latrims
          <span style="color: #ffffff66"> Nigeria </span>
        </b-navbar-brand>
      </nuxt-link>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- <div class="nav_menu"> -->
        <b-navbar-nav class="ml-auto">
          <div class="dropdown">
            <li class="dropbtn">About us</li>
            <div class="dropdown-content">
              <a href="#"> Mission, Vision & Value</a>
              <a href="#">Leadership</a>
              <a href="#" class="last-list">Partners & Clients</a>
            </div>
          </div>
          <div class="dropdown">
            <li class="dropbtn">Produts And Services</li>
            <div class="dropdown-content">
              <a href="#"> Digital Transformation</a>
              <a href="#"> Security Optimization</a>
              <a href="#">Cloud Services Management</a>
              <a href="#">Robotic Process Automation</a>
              <a href="#">Technology Consulting</a>
              <a href="#">Analytics &amp; Reporting</a>
              <a href="#" class="last-list">All Products &amp; Services</a>
            </div>
          </div>
          <div class="dropdown">
            <li class="dropbtn">Resources</li>
            <div class="dropdown-content">
              <a href="#">Marketplace</a>
              <a href="#">Blog</a>
              <a href="#" class="last-list">Customer Success Stories</a>
            </div>
          </div>
          <div class="dropdown">
            <li class="dropbtn">Careers</li>
            <div class="dropdown-content">
              <a href="#" class="last-list">Contact Us</a>
            </div>
          </div>
          <b-button pill style="background-color: #e04b26">Contact Us</b-button>
        </b-navbar-nav>
        <!-- <div class="menu"> -->
        <!-- <div class="dropdown">
              <li class="dropbtn">About us</li>
              <div class="dropdown-content">
                <a href="#"> Mission, Vision & Value</a>
                <a href="#">Leadership</a>
                <a href="#" class="last-list">Partners & Clients</a>
              </div>
            </div> -->
        <!-- <div class="dropdown">
              <li class="dropbtn">What We Do</li>
              <div class="dropdown-content">
                <a href="#"> Digital Transformation</a>
                <a href="#"> Security Optimization</a>
                <a href="#">Cloud Services Management</a>
                <a href="#">Robotic Process Automation</a>
                <a href="#">Technology Consulting</a>
                <a href="#">Analytics &amp; Reporting</a>
                <a href="#" class="last-list">All Products &amp; Services</a>
              </div>
            </div> -->
        <!-- <div class="dropdown">
              <li class="dropbtn">Resources</li>
              <div class="dropdown-content">
                <a href="#">Marketplace</a>
                <a href="#">Blog</a>
                <a href="#" class="last-list">Customer Success Stories</a>
              </div> -->
        <!-- </div> -->
        <!-- <div class="dropdown">
              <li class="dropbtn">Careers</li>
              <div class="dropdown-content">
                <a href="#" class="last-list">Contact Us</a>
              </div>
            </div> -->

        <!-- <b-button pill style="background-color: #e04b26;">Contact Us</b-button> -->
        <!-- </div>
        </div> -->
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
a,
.menu {
  font-size: 12px;
  color: #fff;
  /* background-color: #2b2d42; */
}
.dropdown {
  position: relative;
  display: inline-block;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 180px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  border-radius: 8px;
  border: 2px solid #2b2d42;
  margin: 0.5rem;
  width: 15px;
  font-family: 'Montserrat', sans-serif;
  background-color: #2b2d42;
}
.dropbtn {
  background-color: transparent;
  color: white;
  /* padding: 16px; */
  /* font-size: 16px; */
  border: none;
  font-family: 'Montserrat', sans-serif;
}
.dropdown-content a {
  color: #fff;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  border-bottom: 1px solid rgb(107, 102, 102);
}
.last-list {
  border-bottom: 0;
}
.dropdown-content a:hover {
  background-color: #e04b26;
}

.dropdown:hover .dropdown-content {
  display: block;
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
  padding-top: 2rem;
  padding-bottom: 1.5rem;
  text-align: center;
  align-items: center;
  padding-left: 3rem;
  /* position: fixed; */
  /* background-color: transparent; */
}
.menu {
  font-weight: 400;
  font-size: 15px;
  display: flex;
  list-style: none;
  justify-content: space-around;
}
.logo {
  color: #fff;
  font-size: 20px;
  font-weight: 700;
  position: relative;
  text-decoration: none;
  font-family: 'Poppins', sans-serif;
}
button {
  font-family: 'Montserrat', sans-serif;
}
</style>
