<template>
    <header>
        <nav>
            <router-link to="/">Home</router-link>
            <router-link to="/filmes">Filmes</router-link>
            <router-link to="/tv">Séries</router-link>
        </nav>
    </header>
</template>

<style scoped>
header {
    background-color: #2c3e50; 
    color: #ffffff; 
    padding: 1rem;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3); 
}

nav {
    display: flex;
    justify-content: center; 
    column-gap: 2rem;
}

nav a {
    text-decoration: none;
    color: #ffffff; 
    font-weight: bold; 
    transition: color 0.3s; 
}

nav a:hover {
    color: #f39c12; 
}
</style>