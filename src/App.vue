<template>
  <v-app>
    <v-main>
      <AppToolBar/>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
  import AppToolBar from './components/shared/AppToolBar';
  export default {
    name: 'App',
    components: {
      AppToolBar
    }
  }
</script>

<style>

</style>