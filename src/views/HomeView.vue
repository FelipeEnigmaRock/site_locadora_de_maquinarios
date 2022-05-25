<template>
  <div class="home">
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import About from '../components/About.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar,
    About
  }
}
</script>
