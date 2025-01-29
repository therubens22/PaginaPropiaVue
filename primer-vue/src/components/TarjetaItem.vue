<template>
  <div class="tarjeta">
    <h2>{{ titulo }}</h2>
    <p>{{ descripcion }}</p>
  </div>
</template>

<script>
export default {
  name: 'TarjetaItem',  // El nombre del componente debe ser igual al que usas en App.vue
  props: {
    titulo: String,
    descripcion: String
  }
}
</script>

<style scoped>
.tarjeta {
  border: 1px solid #ccc;
  padding: 16px;
  margin: 10px;
  border-radius: 8px;
  background-color: #f9f9f9;
}

h2 {
  color: #333;
}

p {
  color: #666;
}
</style>
