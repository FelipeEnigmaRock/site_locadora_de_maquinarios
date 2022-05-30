<template>
  <div class="main-navbar">
    <router-link to="/"> <img class="logo" src="../assets/img/logo1.png" alt="Logo da Construtora Leite"> </router-link>
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
  

 
}

.logo {
  margin-left: 0;
  margin-right: 40px;
  width: 5.5rem;
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
  color: #ff8040;
}

h1 {
  color: #fff;
  margin-left: 80px;
  margin: auto;
  margin-left: 0;
}

a:hover {
    color: #ff8040;
}

a {
  text-decoration: none;
  color: #fff;
}

@media (max-width: 680px) {
  .main-navbar {
    display: flex;
    justify-content: space-around;
  }
  
  h1 {
  display: none;
}

}

</style>
