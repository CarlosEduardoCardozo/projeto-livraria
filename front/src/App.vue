<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import FooterComp from "@/components/template/FooterComp.vue";
</script>

<template>
  <HeaderComp />
  <main>
    <RouterView />
    <h3>Bem vindo a livraria parte administrativa</h3>
    <h2>Selecione uma área para editar/cadastrar</h2>
  </main>
  <FooterComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: auto;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}

main {
  min-height: 80%;
}

a {
  color: inherit;
  text-decoration: none;
}

h3,
h2 {
  display: flex;
  justify-content: center;
  margin-top: 180px;
  font-size: 35px;
  font-weight: 800;
  color: #3d1a14;
}

h2 {
  margin-top: 0;
  font-weight: 300;
  font-size: 20px;
}
</style>
