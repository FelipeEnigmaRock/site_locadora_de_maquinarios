<template>
    <div class="main-footer">
        <router-link to="/"> <img class="logo" src="../assets/img/logo1.png" alt="Logo da Construtora Leite"> </router-link>
        <h1><router-link to="/" class="h1"> CONSTRUTORA LEITE </router-link></h1>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
.main-footer {
    width: 100%;
    padding: 20px;
    background-color: #000;
    display: flex;
    bottom: 0;
    position: fixed;
    justify-content: center;
    align-items: center;
}

.logo {
    width: 7rem;
    margin-right: 40px;
}

.h1 {
    color: #fff;
    text-decoration: none;
}

.h1:hover {
    color: #ff8040;
}

@media (max-width: 680px) {
    .h1 {
        display: none;
    }

    .logo {
        width: 5rem;
    }
}
</style>