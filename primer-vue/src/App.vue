<template>
  <div id="app">
    <TarjetaItem titulo="Mi primera tarjeta" descripcion="Esta es una descripción corta de mi tarjeta." />
    <TarjetaItem titulo="Otra tarjeta" descripcion="Aquí va otra descripción para una tarjeta diferente." />
  </div>
</template>

<script>
import TarjetaItem from './components/TarjetaItem.vue';  <!-- Cambiado a TarjetaItem -->

export default {
  name: 'App',
  components: {
    TarjetaItem  <!-- Cambiado a TarjetaItem -->
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  text-align: center;
}
</style>
