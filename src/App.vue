<script setup>
import Estudios from './components/Estudios.vue';
import Experiencia from './components/Experiencia.vue';
import Habilidades from './components/Habilidades.vue';
import Header from './components/Header.vue';
import Proyectos from './components/Proyectos.vue';
import SobreMi from './components/Sobre-mi.vue';
</script>

<template>
  <div class="container w-full mx-auto">
    <Header />
    <main>
      <SobreMi />
      <Experiencia />
      <Estudios />
      <Habilidades />
      <Proyectos  />
    </main>
  </div>
</template>

<style scoped>
  .container {
    @media (max-width: 1599px) {
      width: 90%;
    }
  }
</style>
