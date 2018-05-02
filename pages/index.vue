<template>
  <section class="container">
    <div>
      <h1 class="title">
        The Viji
      </h1>
      <h2 class="subtitle">
        Making visible what is invisible for the eye
      </h2>
      <div class="links">
        <a href="https://twitter.com/thisistheviji" target="blank"><i class="ion-social-twitter"></i></a>
        <a href="https://www.instagram.com/thisistheviji" taget="blank"><i class="ion-social-instagram"></i></a>
        <a href="https://www.facebook.com/theviji/" target="blank"><i class="ion-social-facebook"></i></a>
      </div>
      <div class="footer">
        Copyright 2016-2018 - The Viji
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.links a i {
	font-size: 40px;
  padding: 20px;
  color:#526488;
}
.footer{
  font-size: x-small;
  padding-top: 40px;
}
</style>
