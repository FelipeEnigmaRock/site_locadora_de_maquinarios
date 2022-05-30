<template>
    <div class="main-about">
        <div class="get-darker">
            
            <p>A Construtora Leite é uma empresa de locação de maquinário pesado, contamos com diversos modelos de retroescavadeiras para suas mais diversas necessidades. Sempre pensamos em como atender de melhor maneira nossos clientes.</p>
        </div>
        <img class="retro-img" src="../assets/img/frotaretro.jpg">
        
    </div>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style scoped>
    .main-about {
        width: 100%;
        height: 25rem;
        min-height: 300px;   
        display: flex;   
        justify-content: center;
        text-shadow: 2px 1px 2px   #fff;
        background-color: #0f0d0d;
        
    }

    .get-darker {
        width: 100%;
        height: 25rem;
        min-height: 300px;
        padding: 20px;
        background-color: rgba(0, 0, 0, 0.7);
        display: flex;
        text-align: center;
        align-items: center;
        color: #fff;
        font-size: 2rem;
        box-shadow: inset 0px 30px 54px -37px #fff;  
        position: absolute;
    }

    .retro-img {
        width: 100%;
        max-width: 1000px;

    }

    @media (max-width: 680px) {
        .get-darker {
            font-size: 1.5rem;
        }
        
    }
</style>