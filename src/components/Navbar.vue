<template>
  <div class="main-navbar">
    <router-link to="/"> <img class="logo" src="../assets/img/Logo.jpg" alt="Construtora Leite"> </router-link>
    <h1><router-link to="/"> CONSTRUTORA LEITE </router-link></h1>
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
  height: 80px;
  width: 100%;
  background-color: #000;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  position: absolute;
 
}

.logo {
  margin-left: 0;
  margin-right: 40px;
}

.inicio,
.fale {
  margin-right: 20px;
  text-decoration: none;
  font-size: 1.5rem;
  color: white;
}

.inicio:hover,
.fale:hover {
  color: rgb(226, 95, 55);
}

.logo {
  width: 5.5rem;
}

h1 {
  color: #fff;
  margin-left: 80px;
  margin: auto;
  margin-left: 0;
}

a {
  text-decoration: none;
  color: #fff;
}

@media (max-width: 680px) {
  h1 {
  color: #000;
  margin-left: 0;
  font-size: 0.01px;
}


}

</style>
