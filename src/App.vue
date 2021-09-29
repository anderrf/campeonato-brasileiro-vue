<template>
  <v-app>
    <v-main>
      <AppToolBar/>
      <Inicio/>
    </v-main>
  </v-app>
</template>

<script>
  import AppToolBar from './components/shared/AppToolBar';
  import Inicio from './components/Inicio';
  export default {
    name: 'App',
    components: {
      AppToolBar,
      Inicio
    }
  }
</script>

<style>

</style>