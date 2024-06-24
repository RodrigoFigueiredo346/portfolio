<template>
    <nav class="header">
        <ul>
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/projetos">Projetos</router-link></li>
            <li><router-link to="/treinamentos">Treinamentos</router-link></li>
            <li><router-link to="/sobre">Sobre</router-link></li>
            <li><router-link to="/contato">Contato</router-link></li>
        </ul>
    </nav>
</template>

<script>
    export default {
        name: 'HeaderComponent',
    };
</script>

<style scoped>
    .header {
        background-color: #f0f0f0;
        padding: 20px;
    }

    .header ul {
        list-style: none;
        margin: 0;
        padding: 0;
    }

    .header li {
        display: inline-block;
        margin-right: 20px;
    }

    .header a {
        text-decoration: none;
        color: #333;
    }
</style>
