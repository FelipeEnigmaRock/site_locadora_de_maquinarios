<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/fontawesome.min.css">
<template>
  <nav>
    <Navbar :logo="logo_src" :alt="app_name" />
    <div>
      <router-view></router-view>
      <div>
        <a href="https://web.whatsapp.com/send?phone=5582993310998" target="_blank">
          <img class="icon-whats" src="./assets/img/whatsapp-icone-6.png">
        </a>
      </div>
    </div>
    <Footer />
  </nav>
</template>

<script>
  import Navbar from "./components/Navbar.vue"
  import Footer from "./components/Footer.vue"

  export default {
    name: 'App',
    components: {
      Navbar,
      Footer
    }
  }
</script>

<style>
* {
padding: 0;
margin: 0;
font-family: sans-serif;
box-sizing: border-box;
font-family: 'Playfair Display', serif;

}

.icon-whats {
  width: 60px;
  height: 60px;
  bottom: 40px;
  right: 40px;
  position: fixed;
  z-index: 1000;
}


</style>
