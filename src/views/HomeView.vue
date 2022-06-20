<template>
  <div class="home">
    <About />
    <Sales />
    
  </div>
</template>

<script>
// @ is an alias to /src
import About from '../components/About.vue'
import Machines from '../components/Machines.vue'
import Sales from '../components/Sales.vue'

export default {
  name: 'HomeView',
  components: {
    About,
    Sales,
    Machines
  }
}
</script>
