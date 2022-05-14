<template>
  <nav>
    <Navbar :logo="logo_src" :alt="app_name" />
    <div>
      <router-view></router-view>
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

}
</style>
