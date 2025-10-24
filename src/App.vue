<template>
  <div class="container">
    <h1>Cotizador de Criptomonedas</h1>
    <Grid>
      <Formulario />
      <Data />
    </Grid>
  </div>
</template>
<script>
import Formulario from './components/Formulario.vue';
import Data from './components/Data.vue';
import Grid from './components/Grid.vue';

export default {
  components: {
    Grid,
    Formulario,
    Data
  }
}
</script>
<style>
  
</style>