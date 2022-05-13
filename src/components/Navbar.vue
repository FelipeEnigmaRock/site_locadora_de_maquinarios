<template>
  <div class="main-navbar">
    <router-link class="inicio" to="/">Início</router-link> 
    <router-link class="fale" to="/about">Fale Conosco</router-link>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  }
}
</script>


<style scoped>
.main-navbar {
  padding: 20px;
  height: 80px;
  background-color: aqua;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  

}

.inicio,
.fale {
  margin-right: 40px;
  text-decoration: none;
  font-size: 2rem;
}

</style>
