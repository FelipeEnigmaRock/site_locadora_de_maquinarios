<template>
  <div class="home">
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import About from '../components/About.vue'
import Sales from '../components/Sales.vue'

export default {
  name: 'HomeView',
  components: {
    About,
    Sales
  }
}
</script>
