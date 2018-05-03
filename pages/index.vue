<template>
  <section>
    <section class="hero is-info is-medium">
      <div class="hero-head">
        <nav class="navbar is-fixed-top">
          <div class="navbar-brand">
            <a class="navbar-item" href="/">
              The Viji
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
            Currently the website is under heavy maintenance.
          </h2>
        </div>
      </div>
    </section>

    <section class="container">
      <div class="intro is-8 is-offset-2">
        <h2 class="title">Making visible what is invisible for the eye!</h2><br>
      </div>
    </section>  

    <section class="container">
      <div class="tile is-ancestor">
        <div class="tile is-parent inverted-tile">
          <article class="tile is-child">
            <p class="title has-text-centered">Visualization</p>
            <p class="has-text-centered">Let us help you visualize your data by giving you new insights in techniques and tools of the Big Data world.</p>
            <div class="has-text-centered">
              <i class="ion-connection-bars"></i>
            </div>            
          </article>
        </div>
        <div class="tile is-parent inverted-tile">
          <article class="tile is-child is-0">
            <p class="title has-text-centered">Online learning</p>
            <p class="has-text-centered">By providing appealing and innovative ways of exposing information we aim to make learning fun again.</p>
            <div class="has-text-centered">
              <i class="ion-ios-monitor-outline"></i>
            </div>
            
          </article>
        </div>
        <div class="tile is-parent inverted-tile">
          <article class="tile is-child">
            <p class="title has-text-centered">Tutorials</p>
            <p class="has-text-centered">We are here to teach people, young to old, starters and experienced people moden ways of engaging with the web.</p>
            <div class="has-text-centered">
              <i class="ion-ios-book-outline"></i>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="container">
      <div class="articles columns">
        <div class="column is-3">          
          <div class="card article">
            <div class="card-content">
              <div class="media">
                <div class="media-center">
                  <img src="http://www.radfaces.com/images/avatars/big-pete-wrigley.jpg" class="author-image" alt="Placeholder image">
                </div>
                <div class="media-content has-text-centered">
                  <p class="title article-title">Finally an easy way to learn</p>
                  <p class="subtitle is-6 article-subtitle">
                    <a href="#">Jan Vanderschoot</a> on February 24, 2018
                  </p>
                </div>
              </div>
              <div class="content article-body">
                <p>I have never really been into culture and history, but TheViji makes it easy to quickly browse to several topics when I have a few minutes of spare time.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="column is-3">
          <div class="card article">
              <div class="card-content">
                <div class="media">
                  <div class="media-center">
                  <img src="http://www.radfaces.com/images/avatars/clarissa-marie-darling.jpg" class="author-image" alt="Placeholder image"> 
                  </div>
                  <div class="media-content has-text-centered">
                    <p class="title article-title">Superb :)</p>
                    <p class="subtitle is-6 article-subtitle">
                      <strong>Tina Nipote</strong> on October 7, 2017
                    </p>
                  </div>
                </div>
                <div class="content article-body">
                  <p>
                    As a girl just starting with school, I find it fun to play on the Vijis learning platform.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="column is-3">
            <div class="card article">
              <div class="card-content">
                <div class="media">
                  <div class="media-center">
                    <img src="http://www.radfaces.com/images/avatars/angela-chase.jpg" class="author-image" alt="Placeholder image">
                  </div>
                  <div class="media-content has-text-centered">
                    <p class="title article-title">Very pleasant experience!</p>
                    <p class="subtitle is-6 article-subtitle">
                      <strong>F. Crawl</strong> on November 12, 2017
                    </p>
                  </div>
                </div>
                <div class="content article-body">
                  <p>
                    While until recently we used to work with Excel sheets and PowerPoints, the Viji provided us with new and faster ways to give insights in our financial situation.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="column is-3">
            <div class="card article">
              <div class="card-content">
                <div class="media">
                  <div class="media-center">
                    <img src="http://www.radfaces.com/images/avatars/scrappy-doo.jpg" class="author-image" alt="Placeholder image">
                  </div>
                  <div class="media-content has-text-centered">
                    <p class="title article-title">Complex but interesting..</p>
                    <p class="subtitle is-6 article-subtitle">
                      <strong>S. Doo</strong> on April 30, 2018
                    </p>
                  </div>
                </div>
                <div class="content article-body">
                  <p>
                    While until recently we used to work with Excel sheets and PowerPoints, the Viji provided us with new and faster ways to give insights in our financial situation.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
    </section>

    <section class="container-fluid">
      <div class="sandbox">
        <div class="tile is-ancestor">
           <div class="tile is-parent">
            <article class="tile is-child notification is-white">
              <p class="title">We create..</p>
              <div class="content">
                <p>Graphs, visuals, charts, you name it. We put data in new formats, shapes and colors!</p>
              </div>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child notification is-white">
              <figure class="image is-6by3">
                <img src="/directed_graph_10.png">
              </figure>
            </article>
          </div>
        </div>
      </div>    
      <div class="tile is-ancestor">
        <div class="tile is-vertical is-8">
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article class="tile is-child notification is-white">
                <p class="title">Vertical tiles</p>
                <p class="subtitle">Top box</p>
              </article>
              <article class="tile is-child notification is-white">
                <p class="title">Vertical tiles</p>
                <p class="subtitle">Bottom box</p>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification is-white">
                <p class="title">Middle box</p>
                <p class="subtitle">With an image</p>
                <figure class="image is-6by3">
                  <img src="/worldmap_final.png">
                </figure>
              </article>
            </div>
          </div>
          <div class="tile is-parent is-shady">
            <article class="tile is-child notification is-white">
              <p class="title">Wide column</p>
              <p class="subtitle">Aligned with the right column</p>
              <figure class="image is-6by3">
                <img src="/areachart_countries.png">
              </figure>
            </article>
          </div>
        </div>
        <div class="tile is-parent is-shady">
          <article class="tile is-child notification is-white">
            <div class="content">
              <p class="title">Tall column</p>
              <p class="subtitle">With even more content</p>
              <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum volutpat tellus diam, consequat gravida libero rhoncus ut. Morbi maximus, leo sit amet vehicula eleifend, nunc dui porta orci, quis semper odio felis ut quam.</p>
                <p>Suspendisse varius ligula in molestie lacinia. Maecenas varius eget ligula a sagittis. Pellentesque interdum, nisl nec interdum maximus, augue diam porttitor lorem, et sollicitudin felis neque sit amet erat. Maecenas imperdiet felis nisi, fringilla luctus felis hendrerit sit amet. Aenean vitae gravida diam, finibus dignissim turpis. Sed eget varius ligula, at volutpat tortor.</p>
                <p>Integer sollicitudin, tortor a mattis commodo, velit urna rhoncus erat, vitae congue lectus dolor consequat libero. Donec leo ligula, maximus et pellentesque sed, gravida a metus. Cras ullamcorper a nunc ac porta. Aliquam ut aliquet lacus, quis faucibus libero. Quisque non semper leo.</p>
              </div>
            </div>
          </article>
        </div>
      </div>

      <div class="tile is-ancestor">
        <div class="tile is-parent">
          <article class="tile is-child notification is-white">
            <p class="title">Side column</p>
            <p class="subtitle">With some content</p>
            <div class="content">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare magna eros, eu pellentesque tortor vestibulum ut. Maecenas non massa sem. Etiam finibus odio quis feugiat facilisis.</p>
            </div>
          </article>
        </div>
        <div class="tile is-parent is-8 is-shady">
          <article class="tile is-child notification is-white">
            <p class="title">Main column</p>
            <p class="subtitle">With some content</p>
            <figure class="image is-6by3">
              <img src="/stacked_bar_creationyears.png">
            </figure>
          </article>
        </div>
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
  color: rgb(10, 86, 130);
  font-family: 'Lato', 'Open Sans', serif;
}
h2.title, .icon i:hover{
  color: rgb(10, 86, 130);
}

.hero-body{
  background: url(https://www.walldevil.com/wallpapers/a80/lake-ontario-toronto-ontario-canada.jpg) no-repeat center center;
  margin-bottom: 50px;
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
.hero.is-info{
  background: #fff;
}
.hero.is-info .navbar-menu, .navbar-brand{
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
.articles {
  margin: 5rem 0;
}
.articles .content p {
    line-height: 1.9;
    margin: 15px 0;
}
.author-image {
    position: absolute;
    top: -30px;
    left: 50%;
    width: 60px;
    height: 60px;
    margin-left: -30px;
    border: 2px solid rgb(10, 86, 130);
    border-radius: 50%;
}
.media-center {
  display: block;
  margin-bottom: 1rem;
}
.media-content {
  margin-top: 3rem;
}
.article, .promo-block {
  margin-top: 6rem;
}
div.column.is-8:first-child {
  padding-top: 0;
  margin-top: 0;
}
.article-title {
  font-size: 2rem;
  font-weight: lighter;
  line-height: 2;
}
.article-subtitle {
  color: #909AA0;
  margin-bottom: 3rem;
}
.article-body {
  line-height: 1.4;
  margin: 0 6rem;
}
.inverted-tile, .inverted-tile i, .inverted-tile p.title{
  color: #fff;
}
.inverted-tile p.title{
  margin-top: 70px;
}
.inverted-tile{
  background: rgb(10, 86, 130);
  margin: 50px;
  padding: 120px;
  display: flex;
  justify-content: center;
  flex-direction: column;
  border-radius: 2000px;
  height: 350px;
  border: 2px solid rgb(10, 86, 130);
  position: relative;
}
.inverted-tile:before {
  background: none;
  border: 2px solid #fff;
  content: "";
  display: block;
  position: absolute;
  top: 2px;
  left: 2px;
  right: 2px;
  bottom: 2px;
  border-radius: 2000px;
  pointer-events: none;
}
.inverted-tile i{
  background: rgb(10, 86, 130);
  font-size: 70px;
}
</style>
