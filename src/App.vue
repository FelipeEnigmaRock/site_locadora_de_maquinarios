<template>
  <nav>
    <Navbar />
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
font-family: 'Playfair Display', serif, Arial;

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
