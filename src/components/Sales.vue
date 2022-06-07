<template>
    <section class="main-sales">
      <h1>Entre em contato conosco</h1>
      <span class="underline"></span>
      <div class="sales-icons">
        <a href="https://web.whatsapp.com/send?phone=5582993310998" target="_blank">
            <div class="whats">
                <img class="icon-whats2" src="../assets/img/whatsapp-icone-6.png" alt="botão do hatsapp">
            </div> 
        </a>
        
        <a href="tel:+5582993310998" target="_blank">
            <div class="fone">
            <img class="icon-fone" src="../assets/img/iconefone.svg" alt="botão do Gmail">
            </div> 
        </a>
        <div class="gmail">
            <a href = "mailto:vagner.leite@hotmail.com.br" target="_blank">
            <img class="icon-gmail" src="../assets/img/Gmail-Logo.wine.svg" alt="botão do Gmail">
        </a>
        </div> 
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
        margin-right: 20px;
        
    }

    .sales-icons div {
        height: 12.5rem;
        max-width: 30rem;
        background-color: #fff;
        border-radius: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 2rem;
        cursor: pointer;
    }

    .sales-icons .whats {
        background: linear-gradient(to bottom, #34af23 5%, #5ad265 100%);
        border:1px solid #4b7a00;
        color: #fff;

    }

    .sales-icons .whats:hover {
        background: linear-gradient(to bottom, #5ad265 5%, #34af23 100%);
    }

    .icon-whats2 {
        width: 5rem;
    }

    .sales-icons .gmail {
        background: linear-gradient(to bottom, #bf211e 5%, #e34133 100%);
        border:1px solid #8a1816;
        color: #fff;

    }

    .sales-icons .gmail:hover {
        background: linear-gradient(to bottom, #e34133 5%, #bf211e 100%);
    }

    .icon-gmail {
        width: 9rem;
    }

    .sales-icons .fone {
        background: linear-gradient(to bottom, #bebebe 5%, #ffffff 100%);
        border:1px solid #555555;
        color: #fff;

    }

    .sales-icons .fone:hover {
        background: linear-gradient(to bottom, #ffffff 5%, #bebebe 100%);
    }

    .icon-fone {
        width: 4rem;
    }

    @media (max-width: 1200px) {
        .sales-icons {
        grid-template-columns: 50% 50%;
        }
    }

    @media (max-width: 860px) {
        .main-sales {
            margin: auto;
            align-items: center;
        }
        
        .sales-icons {
            grid-template-columns: auto;
        }

        .sales-icons div {
            width: 40rem;
        }
    }

    @media (max-width: 500px) {
        .sales-icons div {
            width: 20rem;
        }
    }

    @media (max-width: 380px) {
        .sales-icons div {
            height: 8rem;
            width: auto;
        }

        h1 {
            font-size: 1.2rem;
        }
    }
</style>

