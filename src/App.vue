<template>
  <div id="app">
    <div id="nav" class="container">
      <div>
  <b-navbar toggleable="lg" type="light" variant="">
    <b-navbar-brand href="/" to="/"><img src="./assets/img/logo.png" alt="logo"></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ms-auto">
      <b-nav-item>
        <router-link to="/" class="links">home</router-link>
      </b-nav-item>
        <b-nav-item>
      <router-link to="/clients" class="links">Our Clients</router-link>
        </b-nav-item>
                <b-nav-item>
      <router-link to="/serivces" class="links">Services</router-link>
        </b-nav-item>

      </b-navbar-nav>
      
    </b-collapse>
  </b-navbar>
  </div>
  </div>
  <div>
    <router-view/>
    </div>
<footer>
  <div class="container foot"><p>&copy;2021 copyright designed by Karim Ali</p>
          <div class="logo">
            <i class="fa fa-facebook-official" style="font-size:24px"></i>
            <i class="fa fa-twitter" style="font-size:24px"></i>
            <i class="fa fa-internet-explorer" style="font-size:24px"></i>
        </div>
  </div>
</footer>
  </div>
</template>

<style>
#app {
font-family: 'Cairo', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nav {
  background-color: var(--off-white);
  height: 10vh;
}
#nav img{
  height: 7vh;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: var(--main-color);
}
#nav .links{
  color:var(--second-color);
  text-decoration: none;
  text-transform: uppercase;
  font-weight: bold;
  margin-left: 2vh;
}
#nav .links:hover{
  transition: ease-in-out .5s;
  color: var(--main-color);
}
footer{
  background-color: var(--main-color);
  height: 10vh;
  color: var(--white);

    }
.foot{
  padding-top: 4vh;
  display: flex;
  flex: row;
  justify-content: space-between;

}
/* Small */
@media (min-width: 320px) {
.container{
  font-size:calc(var(--default-font) - 6.5px) ;
}
}
/* Medium */
@media (min-width: 768px) {
.container{
  font-size:calc(var(--default-font) - 3px) ;
}
}
  /* Large */
    @media (min-width: 992px) {
    .container {
    font-size:var(--default-font)  ;
        }
}
  /*X Large */

    @media (min-width: 1024px) {
    .container {
    font-size:calc(var(--default-font) + 2px) ;
        }
    }
</style>
