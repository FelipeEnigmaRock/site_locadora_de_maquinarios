<template>
    <div class="main-about">
        <div class="get-darker">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius molestiae esse dicta. Deserunt reiciendis deleniti ipsa accusamus illum corporis rem assumenda. <br>Laudantium praesentium aliquid incidunt natus quam deserunt quibusdam sed.</p>
        </div>
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
        height: 25vw;
        min-height: 300px;
        background-image: url(../assets/img/frotaretro.jpg);
        background-position-y: 750px;   
        display: flex;   
        text-shadow: 2px 1px 2px   #fff;
        
    }

    .get-darker {
        width: 100%;
        height: 25vw;
        min-height: 300px;
        padding: 20px;
        background-color: rgba(0, 0, 0, 0.7);
        display: flex;
        text-align: center;
        text-justify: center;
        color: #fff;
        font-size: 3vw;
        box-shadow: inset 0px 30px 54px -37px #fff;
        
    }

    @media (max-width: 680px) {
        .get-darker {
            font-size: 1.5rem;
        }
        
    }
</style>