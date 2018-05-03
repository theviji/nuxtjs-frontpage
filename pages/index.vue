<template>
  <section>
    <section class="hero is-info is-medium">
      <div class="hero-head">
        <nav class="navbar is-fixed-top">
          <div class="navbar-brand">
            <a class="navbar-item" href="/">
              TheViji.com
            </a>
            <!--
        Using the v-on: directive to listen for the click event and toggle the data property showNav. Also, using the v-bind: directive to reactively update the class attribute 'is-active' based on the showNav property.
        -->
            <div class="navbar-burger" @click="showNav = !showNav" :class="{ 'is-active': showNav }">
              <span></span>
              <span></span>
              <span></span>
            </div>
          </div>
          <!--
        Using the v-bind: directive to reactively update the class attribute 'is-active' based on the showNav property.
        -->
          <div class="navbar-menu" :class="{ 'is-active': showNav }">
            <div class="navbar-start">
              <a class="navbar-item" href="/">
                Home
              </a>
            </div>

            <div class="navbar-end">
              <div class="navbar-item">
                <div class="field is-grouped is-grouped-centered">
                  <p class="control">
                    <a class="button is-white is-outlined" href="https://www.instagram.com/thisistheviji">
                      <span class="icon">
                        <i class="ion-social-instagram"></i>
                      </span>
                    </a>
                  </p>
                  <p class="control">
                    <a class="button is-white is-outlined" href="https://twitter.com/thisistheviji">
                      <span class="icon">
                        <i class="ion-social-twitter"></i>
                      </span>
                    </a>
                  </p>
                  <p class="control">
                    <a class="button is-white is-outlined" href="https://www.facebook.com/theviji/">
                      <span class="icon">
                        <i class="ion-social-facebook"></i>
                      </span>
                    </a>
                  </p>
                  <p class="control">
                    <a class="button is-white is-outlined" href="https://github.com/theviji">
                      <span class="icon">
                        <i class="ion-social-github"></i>
                      </span>
                    </a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </nav>
      </div>
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">
            Welcome to The Viji
          </h1>
          <h2 class="subtitle">
            Currently the website is under heavy maintenance.<br/>Leave your email & get updates when our website is ready.
          </h2>
        </div>
      </div>
    </section>

    <section class="container">
      <div class="columns features">
        <div class="column is-4">
          <div class="card is-shady">
            <div class="card-image has-text-centered">
              <i class="ion-connection-bars"></i>
            </div>
            <div class="card-content">
              <div class="content">
                <h4>Visualization</h4>
                <p>Let us help you visualize your data by given you new insights in techniques and tools of the Big Data world.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="column is-4">
          <div class="card is-shady">
            <div class="card-image has-text-centered">
              <i class="ion-ios-monitor-outline"></i>
            </div>
            <div class="card-content">
              <div class="content">
                <h4>Online learning</h4>
                <p>By providing appealing and innovative ways of exposing information we aim to make learning fun again.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="column is-4">
          <div class="card is-shady">
            <div class="card-image has-text-centered">
              <i class="ion-ios-book-outline"></i>
            </div>
            <div class="card-content">
              <div class="content">
                <h4>Tutorials</h4>
                <p>We are here to teach people, young to old, starters and experienced people moden ways of engaging with the web.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="intro column is-8 is-offset-2">
        <h2 class="title">Making visible what is invisible for the eye!</h2><br>
      </div>
    </section>      

    <footer class="footer">
      <div class="container">
        <div class="content has-text-centered">
          <p>
            Copyright 2016-2018 - <strong>The Viji</strong>
          </p>
          <p>
            <a class="icon" href="https://github.com/theviji">
              <i class="ion-social-github"></i>
            </a>
          </p>
        </div>
      </div>
    </footer>
  </section>
</template>

<script>
export default {
  data () {
    return {
      showNav: false
    }
  },
  components: {
  }
}
</script>

<style>
html,body {
  background: #EFF3F4;
  color: rgb(10, 86, 130);
  font-family: 'Lato', 'Open Sans', serif;
}
h2.title{
  color: rgb(10, 86, 130);
}
.hero-body{
    background: url(https://www.walldevil.com/wallpapers/a80/lake-ontario-toronto-ontario-canada.jpg) no-repeat center center;
}
.hero-body .container {
  max-width: 700px;
}
.hero-body .title {
  color: hsl(192,17%,99%) !important;
  text-shadow: -2px 0 4px rgb(10, 86, 130), 0 2px 4px rgb(10, 86, 130), 2px 0 4px rgb(10, 86, 130), 0 -2px 4px rgb(10, 86, 130);
}
.hero-body .subtitle {
  color: hsl(192,17%,99%) !important;
  padding-top: 2rem;
  line-height: 1.5;
  text-shadow: -2px 0 4px rgb(10, 86, 130), 0 2px 4px rgb(10, 86, 130), 2px 0 4px rgb(10, 86, 130), 0 -2px 4px rgb(10, 86, 130);
}
nav.navbar{
  border-bottom: white 1px solid;
}
.hero.is-info, .hero.is-info .navbar-menu, .navbar-brand{
  background-color: rgb(10, 86, 130);
}
.hero.is-info a.navbar-item:hover{
  background: #fff;
  color: rgb(10, 86, 130);
}
.hero.is-info a:not(.button):not(.dropdown-item):not(.tag):hover{
  color: rgb(10, 86, 130);
}
.features {
  padding: 5rem 0;
}
.box.cta {
  border-radius: 0;
  border-left: none;
  border-right: none;
}
.card-image > i {
  font-size: 8rem;
  padding-top: 2rem;
  padding-bottom: 2rem;
  color: rgb(10, 86, 130);
}
.card-content .content {
  font-size: 14px;
  margin: 1rem 1rem;
}
.card-content .content h4 {
  font-size: 16px;
  font-weight: 700;
}
.card {
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.18);
  margin-bottom: 2rem;
}
.intro {
  padding: 5rem 0;
  text-align: center;
}
.sandbox {
  padding: 5rem 0;
}
.tile.notification {
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.is-shady {
  animation: flyintoright .4s backwards;
  background: #fff;
  box-shadow: rgba(0, 0, 0, .1) 0 1px 0;
  border-radius: 4px;
  display: inline-block;
  margin: 10px;
  position: relative;
  transition: all .2s ease-in-out;
}
.is-shady:hover {
  box-shadow: 0 10px 16px rgba(0, 0, 0, .13), 0 6px 6px rgba(0, 0, 0, .19);
}

.button{
  border-radius: 45px;
}
</style>
