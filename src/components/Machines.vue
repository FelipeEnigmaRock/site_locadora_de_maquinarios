<template>
  <section class="main-machines">
      <h1>Maquinário disponível</h1>
      <span class="underline"></span>
      <div class="rent-equips-container">
          
      </div>
  </section>
</template>

<script>
export default {
    name:'Machines'
}
</script>

<style scoped>
    .main-machines {
        height: auto;
        display: flex;
        padding: 1rem;
        flex-direction: column;
        background-color: #0f0d0d;
    }

    h1 {
        color: #e6e4e4;
        font-size: 2rem;
        margin: 20px 0 5px 20px;

    }

    .underline {
        height: 4px;
        width: 100%;
        margin-bottom: 20px;
        background-color: #e6e4e4;
        background: linear-gradient(90deg, rgba(255,255,255,1) 0%, rgba(230,228,228,1) 10%, rgba(15,13,13,1) 90%);
        border-radius: 9999px;
    }

    .rent-equips-container {
        height: 1500px;
        width: 1000px;
        margin: auto;
        
        background-color: rgb(54, 54, 54);
    }
</style>