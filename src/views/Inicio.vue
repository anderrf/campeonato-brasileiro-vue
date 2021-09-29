<template>
  <v-container>
    <h2 class="text-h5 text-center mb-3 mt-5">Brasileirão Série A</h2>
    <div class="inicio-imagem">
        <v-img class="inicio-imagem mb-4" src="https://diariodonordeste.verdesmares.com.br/image/contentid/policy:1.2974821:1596806515/Serie-A.png"></v-img>
    </div>
    <p class="text-justify">A Série A do Campeonato Brasileiro de Futebol de 2020, oficialmente Brasileirão Assaí – Série A 2020 por motivos de patrocínio, é a 64.ª edição da principal divisão do futebol brasileiro. A disputa tem o mesmo regulamento dos anos anteriores, quando foi implementado o sistema de pontos corridos.</p>
  </v-container>
</template>

<script>
    export default {
        name: 'Inicio'
    }
</script>

<style scoped>
    .inicio-imagem{
        position: relative;
    }

    .inicio-imagem::after{
        content: '';
        position: absolute;
        left: 0; top: 0;
        width: 100%; height: 100%;
        background: linear-gradient(to right, #121212 0%, rgba(0, 0, 0, 0) 10%, rgba(0, 0, 0, 0) 90%, #121212 100%);
    }
</style>