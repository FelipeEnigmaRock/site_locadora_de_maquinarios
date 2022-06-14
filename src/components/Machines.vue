<template>
  <section class="main-machines">
      <h1>Maquinário disponível</h1>
      <span class="underline"></span>
      <div class="items-wrapper">
          <div class="items">
            <div class="item"><img src= "../assets/img/retroescavadeira-case-580n-01.avif"></div>
            <div class="item"><img src= "../assets/img/retroescavadeira-case-580n-02.avif"></div>
            <div class="item"><img src= "../assets/img/retroescavadeira-case-580n-01.avif"></div>
            <div class="item"><img src= "../assets/img/retroescavadeira-case-580n-02.avif"></div>
            <div class="item"><img src= "../assets/img/retroescavadeira-case-580n-01.avif"></div>
            
          </div>
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
        background-color:#0f0d0d ;
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

    .items-wrapper {
        height: auto;
        width: 100%;
        background-color: rgba(202, 28, 28, 0.192);
        display: flex;
    }

    .items {
        height: 100vh;
        width: 100%;
        background-color: aqua;
    }

    .item {
        height: 200px;
        width: 200px;
        overflow: hidden;
    }
    img {
        max-height: 100%;
        max-width: 100%;
        overflow: hidden;
    }

    @media (max-width:380px) {
        h1 {
            font-size: 1.2rem;
        }
    }
</style>