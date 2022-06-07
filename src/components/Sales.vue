<template>
    <section class="main-sales">
      <h1>Entre em contato conosco</h1>
      <span class="underline"></span>
      <div class="sales-icons">
         <div class="whats">Whatsapp</div> 
         <div class="fone">Fone</div> 
         <div class="gmail">Gmail</div> 
         <div class="insta">Instagram</div> 
         <div class="facebook">Facebook</div> 
      </div>
  </section>
</template>

<script>
export default {
    name: 'Sales'
}
</script>

<style scoped>
    .main-sales {
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

    .sales-icons {
        display: grid;
        color: #000;
        grid-template-columns: 33% 33% 33%;
        gap: 20px;
        
    }

    .sales-icons div {
        height: 12.5rem;
        width: 22rem;
        background-color: #fff;
        border-radius: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    @media (max-width: 1200px) {
        .sales-icons {
        grid-template-columns: 50% 50%;
        }
    }

    @media (max-width: 860px) {
        .main-sales {
            align-items: center;
        }
        
        .sales-icons {
            grid-template-columns: auto;
        }
    }

    @media (max-width: 380px) {
        .sales-icons div {
            height: 8rem;
            width: 15rem;
        }

        h1 {
            font-size: 1.2rem;
        }
    }
</style>

