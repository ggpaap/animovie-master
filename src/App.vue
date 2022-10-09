<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <h1>
        Animovies
    </h1>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/CategoriasView">Categorias</RouterLink>
      </nav>
  </header>
  <RouterView />
</template>

<style scoped>

header {
    background-color: aqua;
    height: 125px;
    width: 1905px;

    padding: 0;
}

h1 {
   

}
</style>
